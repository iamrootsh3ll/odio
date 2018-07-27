# Odio
A Simple Utility to Download Youtube Videos Using Only Clipboard/PasteBoard

# Description
Odio is a shell script which works on MacOS and Linux distributions. It allows you to download music by simply copying the video link from YouTube. No need of pasting the link in a tool and/or Terminal.
Just copy the URL of your favourite music video and it'll start downloading the audio version from that page (if available)


# In Working

A working demonstration of `odio` on MacOS - [Watch on YouTube](https://www.youtube.com/watch?v=BrEVY3E9_bw)

# Dependencies

It highly depends on **youtube-dl** ( http://rg3.github.io/youtube-dl/ ) and **ffmpeg** utility.

## Installing Dependencies
Installing `youtube-dl` and `ffmpeg`

On **Ubuntu**:

```
sudo apt update
sudo apt install youtube-dl ffmpeg
```

On **MacOS**:

`brew install youtube-dl ffmpeg`

# Installing Odio

Open Terminal and run the following commands: 

```
git clone https://github.com/iamrootsh3ll/odio
cd odio
chmod +x odio
sudo cp odio /usr/local/bin/
```

Now simply run `odio` in your Terminal, and Odio will start downloading your favourite music in current working directory of the Terminal. See `pwd`

# Author

Hardeep Singh, Founder of rootsh3ll.com. A Penetration Testing and Security training website for professionals looking to up their game in the field of Netowrk Security.

Hardeep is a Wireless Security Researcher and is looking forward for his research paper to be published this yerar at Bsides Conference.
A research paper on WiFi Hacking Cloud Labs, which allows a student to perform wireless attacks without actually transmitting a single WiFi packet into the real air. This will allow more and more people to get theirs hand on WiFi Security field, motivating more people to learn,sahre and expand the WiFi Security field.

Based on his research paper Hardeep is currently working on [Wireless Security Video Course for Red and Blue Teams](http://rootsh3ll.com/wireless-security-video-course/). It is a 12-week cloud based WiFIi Hacking course where you do not need to invest any money in expensive WiFi cards/routers and time in building the lab setup for yourself. It is totally cloud driven course. 
To start learning all you need is a basic laptop/Desktop computer with a browser. You'll log into your Kali machine via browser/SSH and start hacking right away. No VMs, No WiFi cards are involved ever!

Course starts from the very basics of WiFi netrworking and linux, takes you through the various methodologies used to perform WiFi netrwork penetration tests and graduates in the final month with all th methods/tools and techniques used to secure a WiFi Network. 

We create dashboard, we detect rogue devices connected to our network, we detect netwqork anomalies, we create visualisations, we use Splunk>! 

This is one of it's kind course since there is no other service provider who provides WiFi sniffing, monitoring and hacking course in the cloud. So you have it!

Starting August 2018. Read all about the course here: https://rootsh3ll.com/wireless-security-video-course/
