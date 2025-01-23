# DevOps-roadmap-with-sewar 📜 🔍
### In This valuable roadmap, we will unlock the reality! 🔓

#### Part One: Roadmap Overview 
By the end of our demo, you will be able to answer the following questions: 
- What is DevOps and DevOps methodology
- What are the stages in the DevOps lifcycle
- DevOps benefits and what did it solve
- Distinguish between DevOps vs SRE
- What are the used tools in a DevOps engineer work, and what is the role of each tool
- What are the best text editors can be used as a DevOps Engineer and overview on vim and nano
- What do we mean by CI/CD pipelines and how do jenkins handle this process
- What is the difference between Containerization and Virtualization

The Basic Foundation Topics that we will cover them before starting: 

- Linux
-  Networking Concepts
- OS conceptes
- System monitoring 

What are the tools that we will talk about them? 
- Terraform for Infrastructure automation
- Ansible for configuration managment
- Vagrant for virtualization
- Kubernetes and Prometheus for monitoring, Alerting, and visualizing the metrics data
- Jenkins for CI/CD pipelining

#### Part Two: Foundation Topics (Linux 🐧)
##### 2.1 Linux Commands
you should know the basic linux commands and how to use them, what are the most popular options used with these commands. 
The following list contains some of the linux commands you can start with them for now, dont forget to search for their options also: 
- pwd
- mkdir
- cd
- touch
- ls
- cp
- grep
- chmod
- cat
- pipe command
- mv
- rm and rmdir
- sort
- head and tail
- top command for process observation
- dig command

##### 💡 Let we talk about dig command (due to its high importance) 

dig is an abbreviation for (Domain Information Grouper) : it used for making different DNS (domain name system) queries  
###### Quick Experiment: 
I tried to run this command : dig www.ritaj.com and this is the result:   

 ======================================================================================================    
 
; <<>> DiG 9.18.28-0ubuntu0.24.04.1-Ubuntu <<>> www.ritaj.com  

;; global options: +cmd  

;; Got answer:  

;; ->>HEADER<<- opcode: QUERY, status: NXDOMAIN, id: 551  

;; flags: qr rd ra; QUERY: 1, ANSWER: 0, AUTHORITY: 1, ADDITIONAL: 1  


;; OPT PSEUDOSECTION:  

; EDNS: version: 0, flags:; udp: 65494  

;; QUESTION SECTION:  

;www.ritaj.com.			IN	A  


;; AUTHORITY SECTION:  

ritaj.com.		1800	IN	SOA	natasha.ns.cloudflare.com. dns.cloudflare.com. 2363034226 10000 2400 604800 1800  


;; Query time: 398 msec  

;; SERVER: 127.0.0.53#53(127.0.0.53) (UDP)  

;; WHEN: Thu Jan 23 19:31:14 EET 2025  

;; MSG SIZE  rcvd: 104     



============================================================================================================   



==> You can see more about dig command in this link: 
https://www.cloudns.net/blog/10-most-used-dig-commands/

for more info, check this :
 https://www.digitalocean.com/community/tutorials/linux-commands




