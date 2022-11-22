# Home-Demolisher
PoC for CVE-2021-31166 and CVE-2022-21907


## Usage:
```
usage: CVE-2021-31166.py [-h] [-u URL] [-l LIST] [-o OUTPUT]

Description message

options:
  -h, --help            show this help message and exit
  -u URL, --url URL     IIS Server url. For instance: 192.168.1.110
  -l LIST, --list LIST  IIS Server urls list. For instance: subdomain.txt
  -o OUTPUT, --output OUTPUT
                        Output file to write found issues/vulnerabilities. For instance: output.txt
```

## Samples:
```
python CVE-2021-31166.py -u http://192.168.243.129 -o output.txt
python CVE-2022-21907.py -l subdomain.txt -o output.txt
```

## legal disclaimer: 
Usage of "Home-Demolisher
" for attacking targets without prior mutual consent is illegal. It is the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program
