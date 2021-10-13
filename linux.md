
# linux-1
ls

cat flag
 
# linux-2

ls -al

# linux-3

cat hex.txt

xxd -r -p hex.txt

# linux-4

cat base64.txt

base64 -d base64.txt

# linux-5

find / -name secret

# linux-6


ps aux w | grep socat


root       24408  0.0  0.0  24360  2888 pts/0    S    Oct12   0:00 socat TCP-LISTEN:2111,reuseaddr,fork EXEC:/bin/flag


socat  TCP-LISTEN:2111,reuseaddr,fork EXEC:/bin/flag


# linux-7

- 網路服務==>  netstat
 
- netstat -ano
  - a
  - n
  - 0
- curl 127.0.0.1

# linux-8

- 下載和解壓縮ForYou檔案

  - tar zxvf ForYou.tar.gz


# linux-9

file TobeExe

TobeExe: ELF 32-bit LSB executable, Intel 80386, version 1 (SYSV), dynamically linked, 
interpreter /lib/ld-linux.so.2, for GNU/Linux 2.6.32, BuildID[sha1]=10558357d3700c05f1426a6d2a09b920bda2e464, not stripped


ls -al TobeExe

-rw-r--r-- 1 lab lab 7348 Nov 15  2017 TobeExe

chmod +x TobeExe


ls -al TobeExe
-rwxr-xr-x 1 lab lab 7348 Nov 15  2017 TobeExe


./TobeExe
# linux-10

mkdir /tmp/4100E104

cd /tmp/4100E104

wget http://120.114.62.217/reverse

file reverse

chmod +x reverse

./reverse

strings reverse | grep flag

strings reverse | grep CTF
