# :bomb: YuaxN_Prank
## Modern Denial-of-service ToolKit


  
</p>



 
</p>

# :satellite: Methods:
| Method               |   Target   | Description |
| ---------------------| -----------|-------------|
| SMS                  | PHONE     | Sends a massive amount of SMS messages and calls to a single target |
| EMAIL                | EMAIL     | Sends a massive amount of Email messages to a target |
    

# :gift: Installation:


* Linux:
  * `sudo apt update`
  * `sudo apt install python3 python3-pip git -y`
  * `git clone https://github.com/yuaxen/sms-call.prank`
  * `cd sms-call.prank/`
  * `pip3 install -r requirements.txt`
  * `python3 impulse.py --help`

* Termux:
  * `pkg update`
  * `pkg install python3 python3-pip git -y`
  * `git clone https://github.com/yuaxen/sms-call.prank`
  * `cd sms-call.prank/`
  * `pip3 install -r requirements.txt`
  * `python3 impulse.py --help`

# :phone: Example SMS & Call flood:
```python3 impulse.py --method SMS --time 20 --threads 15 --target +380123456789```

<p align="center">
  <img src="https://i.ibb.co/KmPnV9f/Impulse-SMS.png">
</p>

