# Cowrie Honeypot Setup 

 

Cowrie is a medium-interaction SSH honeypot designed to log brute-force attacks and attacker shell interaction. 

 

## Installation 

 

Clone Cowrie repository 

 

git clone https://github.com/cowrie/cowrie.git 

 

Navigate to directory 

 

cd cowrie 

 

Install dependencies 

 

pip install -r requirements.txt 

 

Start Cowrie 

 

bin/cowrie start 

 

## Logs 

 

Cowrie stores logs in: 

 

var/log/cowrie/ 

 

These logs are later forwarded to Elasticsearch using Filebeat
