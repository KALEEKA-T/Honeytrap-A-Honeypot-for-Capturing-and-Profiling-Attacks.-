# Setup Instructions 

 

## Step 1: Install Required Packages 

Update system packages. 

 

sudo apt update 

sudo apt upgrade 

 

## Step 2: Install Cowrie Honeypot 

 

Clone the Cowrie repository. 

 

git clone https://github.com/cowrie/cowrie.git 

 ## Step 3: Install Elasticsearch 

 

sudo apt install elasticsearch 

 

Start Elasticsearch. 

 

sudo systemctl start elasticsearch 

 

Check status. 

 

sudo systemctl status elasticsearch 

 

## Step 4: Install Kibana 

 

sudo apt install kibana 

 

Start Kibana. 

 

sudo systemctl start kibana 

 

Check status. 

 

sudo systemctl status kibana 

 

## Step 5: Install Filebeat 

 

sudo apt install filebeat 

 

Configure Filebeat to monitor Cowrie logs. 

 

## Step 6: Open Kibana Dashboard 

 

Open browser and go to: 

 

http://localhost:5601 

 

Create visualizations and dashboards for attack monitoring. 
