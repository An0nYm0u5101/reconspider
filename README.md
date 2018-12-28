<h1 align="center">
	<a href="https://github.com/bhavsec/reconspider"><img src="http://reconspider.com/images/reconspider.png" alt="ReconSpider 		height="200" width="200""></a>
</h1>
<h4 align="center"> Most advanced Open Source Intelligence (OSINT) Framework </h4>
<p align="center">
	<img src="https://img.shields.io/badge/release-1.0.2%20(beta)-blue.svg">
</p>

# ReconSpider

ReconSpider is most advanced Open Source Intelligence (OSINT) Framework for scanning IP Address, Emails, Websites, Organizations and find out information from different sources.

ReconSpider can be used by Infosec Researchers, Penetration Testers, Bug Hunters and Cyber Crime Investigators to find deep information about their target.

ReconSpider aggregate all the raw data, visualize it on a dashboard and facilitate alerting and monitoring on the data.



# Table Of Contents

1. [Version (beta)](https://github.com/bhavsec/reconspider#version-beta)
2. [Overview of the tool](https://github.com/bhavsec/reconspider#overview-of-the-tool)
3. [Mind Map (v1)](https://github.com/bhavsec/reconspider#mind-map-v1)
4. [License Information](https://github.com/bhavsec/reconspider#license-information)
5. [ReconSpider Banner](https://github.com/bhavsec/reconspider#reconspider-banner)
6. [Documentation](https://github.com/bhavsec/reconspider#documentation)
7. [Setting up the environment (Linux Operating System)](https://github.com/bhavsec/reconspider#setting-up-the-environment-linux-operating-system)
8. [Setting up the environment (Windows Operating System)](https://github.com/bhavsec/reconspider#setting-up-the-environment-windows-operating-system)
9. [Usage](https://github.com/bhavsec/reconspider#usage)
10. [Note](https://github.com/bhavsec/reconspider#note )



# Version (beta)

  	ReconSpider   :     1.0.5
  	Website       :     reconspider.com



# Overview of the tool:

* Performs OSINT scan on a IP Address, Emails, Websites, Organizations and find out information from different sources.
* Correlates and collaborate the results, show them in a consolidated manner. 
* Use specific script / launch automated OSINT for consolidated data.
* Currently available in only Command Line Interface (CLI).



# Mind Map (v1)

Check out our mind map to see visually organize information of this tool regarding api, services and techniques and more.
```
http://reconspider.com/mindmap.html
```



# License Information
```
ReconSpider and its documents are covered under GPL-3.0 (General Public License v3.0)
```



## ReconSpider Banner

```
__________                               _________       __     ___            
\______   \ ____   ____  ____   ____    /   _____/_____ |__| __| _/___________ 
 |       _// __ \_/ ___\/  _ \ /    \   \_____  \\____ \|  |/ __ |/ __ \_  __ \
 |    |   \  ___/\  \__(  <_> )   |  \  /        \  |_> >  / /_/ \  ___/|  | \/
 |____|_  /\___  >\___  >____/|___|  / /_______  /   __/|__\____ |\___  >__|   
        \/     \/     \/           \/          \/|__|           \/    \/       

                      developer: https://bhavkaran.com


usage: python reconspider.py [OPTIONS]

OPTIONS:

--ip        , -i        Enumerate information from IP Address
--url       , -u        Gather information from given Website
--whois     , -w        Gather domain registration information
--portscan  , -p        Discover hosts and services on a network
--nslookup  , -ns       Obtain domain name or IP address mapping
--honeypot  , -hp       Check if it's honeypot or a real control system
```



# Documentation

Installing and using ReconSpider is very easy. Installation process is very simple.

1. Downloading or cloning ReconSpider github repository.
2. Downloading and installing all dependencies.

Let's Begin !!



### Setting up the environment (Linux Operating System)

Step 1 - Cloning ReconSpider on your linux system.

In order to download ReconSpider simply clone the github repository. Below is the command which you can use in order to clone ReconSpider repository.
```
git clone https://github.com/bhavsec/reconspider.git
```


Step 2 - Installing all dependencies.

Once you clone, you will find directory name as **reconspider**. Just go to that directory and install using these commands:
```
cd reconspider
sudo python setup.py install
```



### Setting up the environment (Windows Operating System)

Step 1 - Downloading ReconSpider on your windows system.

In order to download ReconSpider from github repository simply copy and paste this URL in your favourite browser.
```
https://github.com/bhavsec/reconspider/archive/master.zip
```

Step 2 - Unzipping the file

Once you download, you will find zipped file name as **datasploit-master.zip**. Just right click on that zipped file and unzip the file using any software like [WinZip](https://www.winzip.com/), [WinRAR](https://www.win-rar.com).


Step 2 - Installing all dependencies.

After unzipping, go to that directory using Command Prompt and type the following command.
```
python setup.py install
```



# Developer

    Name                BhavKaran
    Twitter:            @bhavsec
    Facebook:           fb.com/Mr.BhavKaran
    LinkedIn:           linkedin.com/in/bhav
    Website:            bhavkaran.com



# Usage 


ReconSpider is very handy tool and easy to use. All you have to do is just have to pass values to parameter. 
In order to start ReconSpider just type:
```
python reconspider.py
```

**--ip**

This option gathers all the information of given IP Address from public resources.
```
python reconspider.py --ip 8.8.8.8
```

**--url**

This option gathers all the information of given URL Address from public sources and give you in depth-information of IP address, country, city, organization, ISP, open ports and so more.
``` 
python reconspider.py --url google.com 
```

**--whois**

This option allows you to search for domain name availability and WHOIS information including name, organisation, address, city, country, zipcode, registrar, name servers etc.
```
python reconspider.py --whois google.com
```

**--portscan**

This option allows you to determine what hosts are available on the network, what services (application name and version) those hosts are offering, what operating systems (and OS versions) they are running, what type of packet filters/firewalls are in use, and dozens of other characteristics.
```
python reconspider.py --portscan google.com
```

**--nslookup**

This option allows you to obtain information about internet servers. It finds name server information for domains by querying the Domain Name System.
```
python reconspider.py --nslookup google.com
```

**--honeypot**

This option allows you to identify honeypots! The probability that an IP is a honeypot is captured in a "Honeyscore" value that can range from 0.0 to 1.0
```
python reconspider.py --honeypot google.com
```

# Note
```
Currently project is in developement phase and lot of work is going on. Custom error handling is also not implemented, and all the focus is to create required functionality. 
```
