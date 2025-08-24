# darkboss1-Country-Based-Fbid-Clone

darkboss1-Country-Based Fbid-Clone is a powerful Termux-based script for cloning Facebook accounts using advanced and updated methods.  
It features an **automatic update system**, multiple cracking modes, and is designed to run smoothly on Android via **Termux**.

> ⚠️ **For educational and research purposes only. Use responsibly.**

---

##  Termux Installation Guide

###  Requirements

-  Termux (from F-Droid or GitHub)
-  Internet connection
-  Android 7+ recommended
-  `/sdcard/darkboss1-Country-Based Fbid-Clone` directory (used by the tool)

---

###  Installation Steps

```bash
pkg update && pkg upgrade -y
pkg install python git -y
pkg install libandroid-support
rm -rf darkboss1-Country-Based-Fbid-Clone
git clone --depth=1 https://github.com/darkboss1/darkboss1-Country-Based-Fbid-Clone.git
cd darkboss1-Country-Based-Fbid-Clone
pip install pytz
pip install -r requirements.txt
termux-setup-storage
python darkboss1-Country-Based-Fbid-Clone.py
