# opendirectories-bot
## Installation Instructions:

Python 3 is required to run the script.    
```bash
$ sudo apt-get update
$ sudo apt-get install python3.6

$ curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
$ sudo python get-pip.py
```

## Using the Script:
```bash
$ git clone https://github.com/simon987/opendirectories-bot.git
$ cd opendirectories-bot/
$ mkdir static/reports
$ pip3 install -r requirements.txt
$ python3 manual.py mkreport "{{URL}}" "{{6 character id}}"
```

### Example Usage:
```bash
python3 manual.py mkreport "http://example.com/library/ePub/" "123456" 
```
