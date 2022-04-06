# ansible
## five project 
>the essence of the laboratory
>>task:
+ Install Nginx on web1, web2 servers.
+ Install and configure a fail-safe HAProxy+Keepalived bundle on haproxy1, haproxy2 servers. Configure VIP with Keepalived according to the scheme
+ On web1, web2 servers, Nginx should work on port 8080 and give a custom page, going to which you can understand which server you are on.
+ On servers with HAProxy, the software should provide load balancing of web1 and web2 servers in round-robin mode. Make the response timeouts of web1 and web2 as small as possible. Let's say 1-2 seconds
+ Installation and configuration of all software should be provided by Ansible script.
+ Upload all files for this task to Github and write a ReadMe with health screenshots and instructions for running your Ansible script.


##  the script works
### a short work script
# Clone this project


 + copy the repository 
 + through the terminal, go to the copied folder
 + open [Vagrantfile ](https://github.com/Ekaterina04/emamus/blob/main/lab4/Vagrantfile)
 + replacing line 39 `ssh_pub_key = File.readlines("/home/sirius/.ssh/id_rsa.pub").first.strip`
 + +  path to the key
 + write in console `vagrant up` 
 + write in console `ansible-playbook aboba.yml`
 + wait
 + ****we've been waiting a long time****

 + # The server will initialize in the http://192.168.11.100

# this is how the first page should look like

<a href="https://ibb.co/M8hSG1x"><img src="https://i.ibb.co/DGbW8MH/2022-04-06-13-09-31.png" alt="2022-04-06-13-09-31" border="0"></a>

# this is how the second page should look like

<a href="https://ibb.co/31PWByF"><img src="https://i.ibb.co/p2kZJvK/2022-04-06-13-17-42.png" alt="2022-04-06-13-17-42" border="0"></a>
 + # if something is not clear, then look at how Robert did and repeat after [him](https://www.youtube.com/watch?v=ZzvM6_S0HXA)



\

