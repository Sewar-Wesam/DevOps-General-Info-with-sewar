# DevOps-General-Info-with-sewar 📜 🔍
### In This valuable roadmap, we will unlock the reality! 🔓

#### Part One: Roadmap Overview 
By the end of our demo, you will be able to answer the following questions: 
- What is DevOps and DevOps methodology
- What are the stages in the DevOps lifcycle
- DevOps benefits and what did it solve
- Distinguish between DevOps vs SRE
- What are the used tools in a DevOps engineer work, and what is the role of each tool
- What are the best text editors can be used as a DevOps Engineer and overview on some of them like: vim, vi, and nano
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
I tried to run this command : dig www.birzeit.edu and this is the result:   

![Screenshot from 2025-01-23 19-52-15](https://github.com/user-attachments/assets/22cf9b50-3552-4ab8-ba61-a8e668e5dda2)


In the above result, since ritaj (birzeit domain name) uses the cloudflare, so there is one Authority as you can see: Authority: 1 and its relevant information in the authority section.  
There are only one query , in the question section, we are quering about record A. you can try more domain names with dig command. like: dig www.facebook.com and so on so forth.    

If you want to know the IP address for a particular domain name, you can use the dig command without any options as you see in the above result so the IP address for the used domain name is 176.119.250.51    
You can use dig DomainName.com with +short to present a short answer, as shown in the following capture: 
![Screenshot from 2025-01-23 21-29-29](https://github.com/user-attachments/assets/4f56f66f-e14d-48d2-9172-d26fda2c9d36)



Quick Info 🙇🏼‍♀️  

💡 What is the difference between curl and ping commands ?   


• curl: Transfers data from or to a server. So, it is used for web requests and content retrieval.   

--> Works in the Application layer (layer 7) in the OSI model.   

• ping: Checks the connectivity for the remote host if it reachable or not using ICMP packets. So it checks the latency and round trip time.   

--> Works in the network layer (layer 3) in the OSI model.  




==> You can see more about dig command in this link: 
https://www.cloudns.net/blog/10-most-used-dig-commands/  

  


for more info, check this :
 https://www.digitalocean.com/community/tutorials/linux-commands



==> It will be very useful if you watch this video: 
https://www.youtube.com/watch?v=lVLcM-GTDUU

