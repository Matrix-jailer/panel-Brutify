# ADMIN - PANEL - BRUTEFORCE

## Description
This tool help you to find websites admin panels , c-panels


## VERSION
```
0.5
```

## Installation
```
apt install python
```
```
apt install git
```
```
pip2 install colorama
```
```
git clone https://github.com/Matrix-jailer/panel-Brutify.git
```	
		
## Usage
```
cd panel-Brutify
```
```
chmod +x Brute-Panel.py
```
```
python Brute-Panel.py -h
```


## OPTIONS
```
Usage: python Brute-Panel.py --domain <target domain> --progress <index of the page the script reached last run> --page_extension <website language> --strict <True or False> --save <Save the results to a text file?> --verbose <print links as they're tested?> --wordlist <dictionary file to use>--robots <if True don't enter anything else except the domain name>

Options:
  -h, --help            show this help message and exit                                                --domain=DOMAIN       target domain. eg: google.com or www.example.org
  --progress=PROGRESS   (optional) index of the page the script reached last
                        run. The script displays and saves this value in the
                        results file after every run. 0 starts from the
                        beginning.
  --page_extension=PAGE_EXT
                        (optional) whether the website uses html asp php...
                        default value is 'a' which checks everything
  --strict=STRICT       (optional, default False) if True, HTTP codes that
                        correspond to forbidden or authentication required
                        will be ignored.
  --save=SAVE           (optional, default True) if True results will be saved
                        to a txt file.
  --verbose=VERBOSE     (optional, default True) if True each link will be
                        shown as it's being tested.
  --wordlist=WORDLIST   (optional, default is the included wordlist) wordlist
                        file to be used.
  --robots=ROBOTS       (optional, default False) if True the script will try
                        to get the robots.txt file that usually contains the
                        admin panel. If you set it to True, don't
                        enteranything else except the target domain
```

## EXAMPLES
```
python Brute-Panel.py --domain [ Target Domain ] --wordlist admin_login.txt
```
```
python Brute-Panel.py --domain [ Target Domain ] --strict True --save [ example.txt ] --page_extension [ website language ] --verbose True --wordlist admin_login.txt
```


## Contribution
```
If you want to contribute here 
just fork and open a pull request. 
if you have any suggestions to improve this project 
just open an issue.
Found a Problem in Code ?
Open issue asap :-)
```

## Contact
```
Email : usamamuhammad771@gmail.com
```

## Donate
BITCOIN ADDRESS
```
13Gau2D3gjTfCmx7dKjSyZETDH182ZS8ox
```
