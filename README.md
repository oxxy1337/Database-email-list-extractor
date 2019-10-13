
## Database email list extractor
A simple script written in php connect to MySQL database and grab all emails and save them in a file 
### Usage :
```bash
$ ./Extractor 
Usage: ./Extractor [options] 
 Options : 
 -h MySQl Hostname (e.g. 47.102.85.92) 
 -u MySQL Username (e.g. root) 
 -p MySQL Password (e.g. 1234) 
 -f Output Filename (e.g. Subscribers.txt)
 $
```
```bash
$ ./Extractor -h localhost -u root -p toor -f list.txt
Extracting ...
Please wait ...
85517 Email saved in :list.txt
$