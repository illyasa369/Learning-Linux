Level 0
ssh -p 2220 bandit0@bandit.labs.overthewire.org


Level 1
cat readme
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If


Level 2
cat ./-
263JGJPfgU6LtdEvgfWU1XP5yac29mFx


Level 3
cat "spaces in this filename"
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx


Level 4
ls -a
cat ...Hiding-From-You
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ


Level 5
file ./*
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw


Level 6
find ! -executable -size 1033c
HWasnPhtq9AVKe0dmk45nxy20cvUa6EG


Level 7
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj


Level 8
grep millionth data.txt
dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc


Level 9
sort data.txt | uniq -c | grep -w 1
4CKMh1JI91bUIZZPXDqGanal4xvAg0JM


Level 10
strings data.txt | grep ==
FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey


Level 11
base64 -d data.txt
dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr


Level 12
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4


Level 13
mktemp -d
cd tmp/tmp.xxxxxxxxx
Use file to view details about the file.
xxd -r data.txt > tmp.txt
mv tmp.txt tmp.txt.gz
gzip -d tmp.txt.gz
bzip2 -d xxxxxxxx
tar -xf xxxxxxxxxx
...
FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn


Level 14
ssh -i sshkey.private -p 2220 bandit14@bandit.labs.overthewire.org
MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS


Level 15
cat /etc/bandit_pass/bandit14
telnet localhost 30000
8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo


Level 16
openssl s_client localhost:30001
kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx


Level 17
nmap -sV -p31000-32000 localhost
openssl s_client localhost:31790 -ign_eof
openssl s_client -connect localhost:31790 -ign_eof

-----BEGIN RSA PRIVATE KEY-----
MIIEogIBAAKCAQEAvmOkuifmMg6HL2YPIOjon6iWfbp7c3jx34YkYWqUH57SUdyJ
imZzeyGC0gtZPGujUSxiJSWI/oTqexh+cAMTSMlOJf7+BrJObArnxd9Y7YT2bRPQ
Ja6Lzb558YW3FZl87ORiO+rW4LCDCNd2lUvLE/GL2GWyuKN0K5iCd5TbtJzEkQTu
DSt2mcNn4rhAL+JFr56o4T6z8WWAW18BR6yGrMq7Q/kALHYW3OekePQAzL0VUYbW
JGTi65CxbCnzc/w4+mqQyvmzpWtMAzJTzAzQxNbkR2MBGySxDLrjg0LWN6sK7wNX
x0YVztz/zbIkPjfkU1jHS+9EbVNj+D1XFOJuaQIDAQABAoIBABagpxpM1aoLWfvD
KHcj10nqcoBc4oE11aFYQwik7xfW+24pRNuDE6SFthOar69jp5RlLwD1NhPx3iBl
J9nOM8OJ0VToum43UOS8YxF8WwhXriYGnc1sskbwpXOUDc9uX4+UESzH22P29ovd
d8WErY0gPxun8pbJLmxkAtWNhpMvfe0050vk9TL5wqbu9AlbssgTcCXkMQnPw9nC
YNN6DDP2lbcBrvgT9YCNL6C+ZKufD52yOQ9qOkwFTEQpjtF4uNtJom+asvlpmS8A
vLY9r60wYSvmZhNqBUrj7lyCtXMIu1kkd4w7F77k+DjHoAXyxcUp1DGL51sOmama
+TOWWgECgYEA8JtPxP0GRJ+IQkX262jM3dEIkza8ky5moIwUqYdsx0NxHgRRhORT
8c8hAuRBb2G82so8vUHk/fur85OEfc9TncnCY2crpoqsghifKLxrLgtT+qDpfZnx
SatLdt8GfQ85yA7hnWWJ2MxF3NaeSDm75Lsm+tBbAiyc9P2jGRNtMSkCgYEAypHd
HCctNi/FwjulhttFx/rHYKhLidZDFYeiE/v45bN4yFm8x7R/b0iE7KaszX+Exdvt
SghaTdcG0Knyw1bpJVyusavPzpaJMjdJ6tcFhVAbAjm7enCIvGCSx+X3l5SiWg0A
R57hJglezIiVjv3aGwHwvlZvtszK6zV6oXFAu0ECgYAbjo46T4hyP5tJi93V5HDi
Ttiek7xRVxUl+iU7rWkGAXFpMLFteQEsRr7PJ/lemmEY5eTDAFMLy9FL2m9oQWCg
R8VdwSk8r9FGLS+9aKcV5PI/WEKlwgXinB3OhYimtiG2Cg5JCqIZFHxD6MjEGOiu
L8ktHMPvodBwNsSBULpG0QKBgBAplTfC1HOnWiMGOU3KPwYWt0O6CdTkmJOmL8Ni
blh9elyZ9FsGxsgtRBXRsqXuz7wtsQAgLHxbdLq/ZJQ7YfzOKU4ZxEnabvXnvWkU
YOdjHdSOoKvDQNWu6ucyLRAWFuISeXw9a/9p7ftpxm0TSgyvmfLF2MIAEwyzRqaM
77pBAoGAMmjmIJdjp+Ez8duyn3ieo36yrttF5NSsJLAbxFpdlc1gvtGCWW+9Cq0b
dxviW8+TFVEBl1O4f7HVm6EpTscdDxU+bCXWkfjuRb7Dy9GOtt9JPsX8MBTakzh3
vBgsyi/sN3RqRBcGU40fOoZyfAMT8s1m/uYv52O6IgeuZ/ujbjY=
-----END RSA PRIVATE KEY-----


Level 18
diff password.old password.new
x2gLTTjFwMOhQ8oWNbMN362QKxfRqGlO


Level 19
ssh -p 2220 bandit19@bandit.labs.overthewire.org cat readme
cGWpMaKXVwDUNgPAVJbWYuGHVn9zl3j8
