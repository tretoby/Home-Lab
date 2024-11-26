# Phishing Campaign Set Up

## Objective

fully automated and secure phishing campaign simulation platform using AWS to educate and raise awareness about social engineering attacks. This project aims to provide organizations and individuals with hands-on experience in identifying, analyzing, and mitigating phishing threats in a controlled and ethical environment.

### Skills Learned

Cloud Infrastructure:
Deploying and managing AWS services (EC2)

Cybersecurity:
Understanding phishing techniques and defenses.
Simulating social engineering attacks ethically.

Configuring IAM roles, VPCs, and security groups.
Using tools like AWS Shield and WAF for protection.

### Services Used
- AWS
- EC2
- VPC
- GoPhish

## Steps

Download GoPhish Simulator from Amazon marketplace
![gophishsim](https://github.com/user-attachments/assets/6e156195-a85b-43ac-8331-22add031dc9e)

Create a VPC
![createvpc](https://github.com/user-attachments/assets/6ac653e9-72f7-44fc-bf05-3f4ad1dc704e)

choose public subnet created with VPC
![publicsub](https://github.com/user-attachments/assets/98869712-9717-43fa-9a89-5feed3e12fe9)

enable auto-assign public IPV4 address
![ipv4](https://github.com/user-attachments/assets/12e39780-eebb-4501-9bca-976f5ef024e5)

create key pair
![key pair](https://github.com/user-attachments/assets/0642e5d4-e562-4889-a616-cb052b84b614)

create security group
![securitygroup](https://github.com/user-attachments/assets/8450d206-8044-411d-b200-4ac9fc19e08c)

launch instance
![instance](https://github.com/user-attachments/assets/5e61f75d-8c3f-433d-9afa-5d3e8926a1bc)

Wait for instance to initialize 
![image](https://github.com/user-attachments/assets/79b4f23c-1819-443b-b447-409117974db4)

use public address in web browser to find sign in page
![signin](https://github.com/user-attachments/assets/2ebbeaa3-4f15-45fd-a82e-33481b997a33)

login with password (instance ID)
now you can create phishing campaigns for users and groups
![userandgroups](https://github.com/user-attachments/assets/7fa2f599-20af-4d8d-836d-d5600b19b590)

























