Readme

## byte0: 
cd

## byte1:
strace supercalifragilisticexpialidocious

## byte2: 
grep -r "will find" .

## byte3: 
diff shakespeare.txt shakespeare.modified.txt

## byte4: 
find . -name "cup.txt"

## byte5: 
mkdir /tmp/myfolder
cp byte5.c /tmp/myfolder/
gcc byte5.c -o /tmp/myfolder/byte5_executable
./tmp/myfolder/byte5_executable

## byte6: 
mkdir /tmp/byte6_unzip
cp byte6.zip /tmp/byte6_unzip/
cd /tmp/byte6_unzip
unzip byte6.zip


## byte7: 
mkdir /tmp/byte7_extract
mv byte7.tar.gz /tmp/byte7_extract/
cd /tmp/byte7_extract
tar -xzvf byte7.tar.gz


## byte8: 
xxd carriage_return.txt
vim carriage_return.txt και set list

## byte9:
cat /home/byte9/-


## byte10: 
sort ./- | head -n 10 | tail -n 1

## byte11: 
sort births.txt | uniq -c | sort -nr | head -n 1

