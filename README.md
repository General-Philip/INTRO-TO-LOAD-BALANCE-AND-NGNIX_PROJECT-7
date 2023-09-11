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

   2. **Configuring Ngnix as a load balancer** Below are the steps i followed in configuring ngnix as a load balancer:
     a. Provisioned and EC2 instance; made sure port 80 is open to accept traffic from anywhere
     b. Connect my terminal to the ec2 instance and then install ngnix
     c. Next is to configure ngnix as a load balancer
     d. Next we tested the configuration to confirm our syntax is ok with the command; sudo ngnix -t
     e. Ngnix server was restarted then, i ran the IP address(Load balancer) on my browser to see the result

3. **Additional Studies**
After the pratical aspect, i continued with some theoretical studies that helped in understanding loadbalancing more.Below are the studies;
    a. Load balancing algorithms
    b. Some common load balancing algorithms
    c. SSL and HTTPs Loadbalancing ( Concept of Encryption)
    d. Types on Encryption
    e. Purpose of TLS/SSL certificate
    f. Advance Load Balancing features
    g. Key advance load balancing features

Below are screenshots of my steps in the projects

