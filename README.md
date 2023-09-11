# INTRO-TO-LOAD-BALANCE-AND-NGNIX_PROJECT-7

My project 7 started with me understanding the concept "Load balancing" and how it works.

Below are the process in which i executed project 7

1. **Setting up a basic load balancer.** Below steps i followed in setting up the load balancer:
   
     a. Provisioning of 2 Elastic Compute Cloud instances
   
     b. Port configuration; the 2 ec2 instance were configured to run on port 8000 to allow traffic from anywhere
   
     c. Installation of Apache server.
   
     d. Next is the configuration of my Apache webserver to serve contents on port 8000
   
     e. I then created a new HTML file and configured the file with my IP address in my EC2 instance from AWS management console.
   
     f. I changed the ownership of the file running the command sudo chown www-data:www-data ./index.html
   
     g. Next, i overrided the HTML file of Apacha server,restart the web server, and ran the HTML file over the browser.
   

 3. **Configuring Ngnix as a load balancer** Below are the steps i followed in configuring ngnix as a load balancer:
    
     a. Provisioned and EC2 instance; made sure port 80 is open to accept traffic from anywhere
    
     b. Connect my terminal to the ec2 instance and then install ngnix
    
     c. Next is to configure ngnix as a load balancer
    
     d. Next we tested the configuration to confirm our syntax is ok with the command; sudo ngnix -t
    
     e. Ngnix server was restarted then, i ran the IP address(Load balancer) on my browser to see the result

5. **Additional Studies**
After the pratical aspect, i continued with some theoretical studies that helped in understanding loadbalancing more.Below are the studies;

    a. Load balancing algorithms
   
    b. Some common load balancing algorithms
   
    c. SSL and HTTPs Loadbalancing ( Concept of Encryption)
   
    d. Types on Encryption
   
    e. Purpose of TLS/SSL certificate
   
    f. Advance Load Balancing features
   
    g. Key advance load balancing features

Below are screenshots of my steps in the projects

![apache2 active verification](https://github.com/General-Philip/INTRO-TO-LOAD-BALANCE-AND-NGNIX_PROJECT-7/assets/141147192/6b45a85e-5291-4c5c-9335-c8263353ca64)
![apache webserver installation](https://github.com/General-Philip/INTRO-TO-LOAD-BALANCE-AND-NGNIX_PROJECT-7/assets/141147192/e87a3a32-7dae-4485-a7f0-201f45d23834)
![browser outcome_apache](https://github.com/General-Philip/INTRO-TO-LOAD-BALANCE-AND-NGNIX_PROJECT-7/assets/141147192/c713f5cf-c41a-4247-b343-cc89e6d3e611)
![change ownership](https://github.com/General-Philip/INTRO-TO-LOAD-BALANCE-AND-NGNIX_PROJECT-7/assets/141147192/656885d4-892c-4367-92a7-a7f42165b50d)
![connect to ec2](https://github.com/General-Philip/INTRO-TO-LOAD-BALANCE-AND-NGNIX_PROJECT-7/assets/141147192/930db896-9aa3-4a02-8029-b541ea3e7a4d)
![EC2 provisioned instance](https://github.com/General-Philip/INTRO-TO-LOAD-BALANCE-AND-NGNIX_PROJECT-7/assets/141147192/ea726a37-17f6-42e6-9178-01537c2a7d92)
![listen directive for port 8000](https://github.com/General-Philip/INTRO-TO-LOAD-BALANCE-AND-NGNIX_PROJECT-7/assets/141147192/14d1936c-d2e7-4213-ae7e-0741d2258076)
![nginx loadbalancer browser output](https://github.com/General-Philip/INTRO-TO-LOAD-BALANCE-AND-NGNIX_PROJECT-7/assets/141147192/7c39f387-d27d-4bd1-ab7a-0cc2cfcd2ba4)
![nginx loadbalancer configuration check](https://github.com/General-Philip/INTRO-TO-LOAD-BALANCE-AND-NGNIX_PROJECT-7/assets/141147192/028b6ad3-09e5-4d99-a00d-fd865b24251d)
![nginx status](https://github.com/General-Philip/INTRO-TO-LOAD-BALANCE-AND-NGNIX_PROJECT-7/assets/141147192/ec1b4e60-ffd8-4037-8bf0-252ca4889c90)
![New html file](https://github.com/General-Philip/INTRO-TO-LOAD-BALANCE-AND-NGNIX_PROJECT-7/assets/141147192/602d4297-6995-4a7c-810f-bdff688bc9aa)
![nginx load balancer configuration](https://github.com/General-Philip/INTRO-TO-LOAD-BALANCE-AND-NGNIX_PROJECT-7/assets/141147192/36a4fc8b-8cb2-4151-af7a-2d0af6827f9b)
![Overiding the default HTML file and apache2 restart](https://github.com/General-Philip/INTRO-TO-LOAD-BALANCE-AND-NGNIX_PROJECT-7/assets/141147192/690d6cbc-21ba-43d9-b3e2-9211b2566ab8)
![Port configuration](https://github.com/General-Philip/INTRO-TO-LOAD-BALANCE-AND-NGNIX_PROJECT-7/assets/141147192/17b01450-1cd0-42a2-9c86-0ce1262ba19e)
![server 2 for Nginx load balance](https://github.com/General-Philip/INTRO-TO-LOAD-BALANCE-AND-NGNIX_PROJECT-7/assets/141147192/03162840-a648-42b4-9e16-322e69b21f43)
![virtual host change to 8000](https://github.com/General-Philip/INTRO-TO-LOAD-BALANCE-AND-NGNIX_PROJECT-7/assets/141147192/444f9bbd-a4b3-49d9-a6fc-43a330b31c6b)
