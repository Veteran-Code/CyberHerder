# Herder - Data Wrangling All Cyber
[![Test Coverage](https://img.shields.io/badge/Test%20Coverage-100%25-success)](https://github.com/jacob-h-barrow/SiemChirps)
[![Security](https://img.shields.io/badge/Secure-True-informational)](https://github.com/jacob-h-barrow/SiemChirps)
[![Platform](https://img.shields.io/badge/Platform-Ubuntu%2020%2B-critical)](https://github.com/jacob-h-barrow/SiemChirps)
[![Python Version](https://img.shields.io/badge/Python-3.8%2B-critical)](https://github.com/jacob-h-barrow/SiemChirps)
[![MIT License](https://img.shields.io/badge/License-MIT-lightgrey)](https://github.com/jacob-h-barrow/SiemChirps)

![Cyber Herder Banner](https://user-images.githubusercontent.com/112576275/189983108-0f64cd53-0c71-4835-9691-b012f87fbb2a.png)

- Created By Jacob H Barrow

## Why Was It Created
- Data is gold, so learning cybersecurity can be tricky without simulated testbeds.
- Use this package to test singular components, like GPS, Phones, or IPs, or use it across a fake company.

## Why Herder
- Cyber's the Wild West, so let's go back to America's roots.
- It's all about wrangling that data, Yeehaw!!!!
- Also, I was tried of giving out my email and phone number to get cyber datasets!

## Installation
``` console
herder@cyberWrangler:~$ git clone https://github.com/danielmiessler/SecLists.git
herder@cyberWrangler:~$ unzip SecLists-master.zip
herder@cyberWrangler:~$ sudo mkdir /usr/share/wordlists/
herder@cyberWrangler:~$ sudo mv SecLists-master SecLists
herder@cyberWrangler:~$ sudo mv SecLists /usr/share/wordlists/
herder@cyberWrangler:~$ pip install CyberHerder
```

## Usage
``` python
>>> from CyberHerder import generate, terminate, valid, dataBreach
>>>
>>> ipv4s = generate("IPv4", 10)
>>>
>>> valid("IPv4", ipv4s[0])
>>>
>>> not terminate("IPv4", ipv4s[0])
>>>
>>> # Use an absolute destination for this one.
>>> # Funny story, I used the tilde. Then I used rm -r ~. It didnt take only the folder named ~.
>>> dataBreach(amount = 100, dest = "/home/fox/BreachedData/")
```

## Remember
- If you find this package helpful, follow mascots and join Dumbledore's Army!
