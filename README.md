# Holiday MOTD ASCII Art 🎄✨

Celebrate the holidays with a touch of nostalgia and creativity! This repository features my hand-crafted ASCII art for server Message of the Day (MOTD) displays. It’s a simple, festive, and fully customizable way to spread cheer across your servers during the holiday season.

# Description:

A simple customizable holiday themed Message of the Day script designed for Linux based servers. 

# Features 🎁

- Simple Holiday ASCII Art : A cheerful winter holiday design that adds a festive touch to your server login.
- Easy Customization: Modify or adapt the artwork to fit your own message or theme.
- Easy Setup: Just copy, paste, and share the joy—no fancy setup required!

# Installation and Setup 🛠️

Follow these steps to add some holiday cheer to your server's MOTD using the 00-holiday.sh script:

### Download the Repository:
1. Use wget to download the entire repository as a zip file:
  ```bash
  wget https://github.com/anyasciiTV/holiday-motd/archive/main.zip
  ```
2. Extract the Repository:
  ```bash
  unzip main.zip
  cd server-holiday-motd-main
  ```
3. If you don't have unzip, you can install it with the following commands:
  ```bash
  sudo apt install unzip # Debian distros
  sudo yum install unzip # Fedora/Red Hat distros
  ```
4. Copy the 00-holiday.sh script to the MOTD directory on your server:
  ```bash
  sudo cp 00-holiday.sh /etc/motd.d/
  ```
For some distros, the directory might be /etc/motd.d or /etc/motd
5. Make the 00-holiday.sh script executable
```bash
  cd /etc/update-motd.d
  chmod +x 00-holiday.sh 
  ```
6.The MOTD shoud now display whenever a user logs in. You can test it initially on the server with simulating a login:
```bash
  ssh local
  ```

# Building Your Own Designs 🖌️
Want to create your own ASCII art? Start with tools like jp2a for inspiration or go old-school with a plain text editor.

# A Note from the Creator 🌟
This is my first attempt at holiday-themed ASCII art in years, and it’s been a fun project to share. While it’s nothing fancy, I hope it adds a little cheer to your day or inspires you to create your own!

Feel free to tweak the art, build on it, or just enjoy it as is. And if you have ideas or improvements, I'd love to hear them.

Happy Holidays! 🎄

ANYASCII

