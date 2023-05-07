# JeuBanditLevel
Il y a 34 levels et le jeu consiste à trouver le mot de passe pour chaque level

ssh bandit0@bandit.labs.overthewire.org -p 2220 le premier hôte avec mot de passe : bandit0.

level-1:

hôte: ssh bandit0@bandit.labs.overthewire.org -p 2220
ls après
cat dans le fichier readme
mot de passe: NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL

level 2:

hôte: ssh bandit1@bandit.labs.overthewire.org -p 2220
ls
cat ./- pour afficher le mot de passe

mot de passe: rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi

level 3:
hôte: ssh bandit2@bandit.labs.overthewire.org -p 2220
ls
cat ./ spaces +TAB	pour afficher spaces\ in\ this\ filename
mot de passe: aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG

level4:
hôte: ssh bandit3@bandit.labs.overthewire.org -p 2220

ls
cd inhere
cat .hidden

mot de passe: 2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe


level5:
hôte: ssh bandit4@bandit.labs.overthewire.org -p 2220
ls 
cd inhere
cat ./-file07
mot de passe: lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR

level6:

hôte:ssh bandit5@bandit.labs.overthewire.org -p 2220

find inhere -type f -size 1033c -not -executable -exec file {} \; | grep "ASCII text" | cut -d: -f1 | xargs cat

mot de passe: P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU

level7:

hôte: ssh bandit6@bandit.labs.overthewire.org -p 2220
find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null
cat  /var/lib/dpkg/info/bandit7.password
mot de passe: z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S

level 8:
hôte: ssh bandit7@bandit.labs.overthewire.org -p 2220
ls
data.txt
grep "millionth" data.txt

mot de passe: TESKZC0XvTetK0S9xNwm25STk5iWrBvP

level9:
hôte: ssh bandit8@bandit.labs.overthewire.org -p 2220
ls
sort data.text | uniq -u
mot de passe:EN632PlfYiZbn3PhVK3XOGSlNInNE00t

level10:
hôte: ssh bandit9@bandit.labs.overthewire.org -p 2220
ls
strings data.txt | grep "===="

mot de passe: G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s

level11:
hôte: ssh bandit10@bandit.labs.overthewire.org -p 2220
ls
cat data.txt | base64 -d

mot de passe: 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM

level12:
hôte: ssh bandit11@bandit.labs.overthewire.org -p 2220
ls
cat data.txt | tr '[A-Za-z]' '[N-ZA-Mn-za-m]'
mot de passe:JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv

level13:
hôte: ssh bandit12@bandit.labs.overthewire.org -p 2220
mkdir /tmp/newfolder
ls
cat data9


mot de passe:wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw

level14:
hôte: ssh bandit13@bandit.labs.overthewire.org -p 2220
ls
cat sshkey.private
ssh -i sshkey.private bandit14@localhost  -p 2220


level15:
hôte: ssh bandit14@bandit.labs.overthewire.org -p 2220
cd /etc/bandit_pass/
cat bandit14
echo fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq | nc localhost 30000
mdp: jN2kgmIXJ6fShzhT2avhotn4Zcka6tnt

level 16:
ls
cat /etc/bandit_pass/bandit15
openssl s_client -connect localhost:30001
mdp:JQttfApK4SeyHwDlI9SXGR50qclOAil1

level 17:
nmap -A localhost -p 31000-32000
cat /etc/bandit_pass/bandit16
openssl s_client -connect localhost:31790
cd /tmp
nano ssh-17.private
mdp= VwOSWtCA7lRKkTfbr2IDh6awj9RNZM5e

level 18:
ls
diff passwords.new passwords.old
mdp= hga5tuuCLF6fFzUpnagiMN8ssu9LFrdg

level19:
ssh -T bandit18@bandit.labs.overthewire.org -p 2220
ls
cat readme
mdp=awhqfNnAbc1naukrpqDYcF95h7HoMTrC

level20:
ls
file bandit20-do
./bandit20-do
./bandit20-do cat /etc/bandit_pass/bandit20
mdp=VxCazJaVykI6W36BkBU0mJTCM8rR95XT

level21:
ls
echo -n VxCazJaVykI6W36BkBU0mJTCM8rR95XT | nc -l -p 1234 & [1] 2227708
./suconnect 1234
Read: VxCazJaVykI6W36BkBU0mJTCM8rR95XT
Password matches, sending next password
mdp=NvEJF7oVjkddltPSrdKEFOllh9V1IBcq

level 22:
cd /etc/cron.d
ls
cat cronjob_bandit22
cat /usr/bin/cronjob_bandit22.sh
cat /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv
mdp= WdDozAdTM2z9DiFEQ2mGlwngMfj4EZff

level 23:
cd /etc/cron.d
ls
 cat cronjob_bandit23
cat /usr/bin/cronjob_bandit23.sh
echo I am user bandit23 | md5sum | cut -d ' ' -f 1
cat /tmp/8ca319486bfbbc3663ea0fbe81326349
mdp= QYw0Y2aiA672PsMmh9puTQuhoz8SyR2G

level24:
