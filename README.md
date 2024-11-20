 #  EX 6 CREATION IN WEB APPLICATION FOR TEST ENVIRONMENT
 ```
REG NUMBER:212223220032
NAME: HARSETHA J
```
  ## AIM
       To Creation in Web Application for Test Environment.
## PROBLEM STATEMENT
    Explain about the Experiment.

## ALGORITHM
 ### Steps 1:
 Launch an EC2 instance in AWS using an Amazon Linux 2 AMI with a Security Group allowing HTTP and SSH traffic.
 
 ### Steps 2:
 Connect to the instance using SSH and install a web server like Apache

 ### Steps 3:
 Create a simple HTML file in the server's default directory with basic content for testing.
 
 ### Steps 4:
 Access the instance's public IP in a browser to verify the HTML page is displayed.
 
## COMMANDS
### To install httpd:
```
yum install httpd -y
```
### To enable and start httpd :
```
systemctl enable httpd
systemctl start httpd
```

## OUTPUT
### Terminal:
![387069261-3ffc8825-7290-43c9-bdfa-d18ff6d16772](https://github.com/user-attachments/assets/926a391d-c33d-4f65-81b7-132362e510b4)

### Website:
![386834037-f63dc64f-c2ea-4aa8-9d6c-02b56b96adc1](https://github.com/user-attachments/assets/c7f159c9-c8ad-4f70-a610-fbb448cab4c9)

## RESULT
 Thus the web application for test environment has successfully been created and executed.

  


