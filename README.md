# Phishing Campaign Setup

## Objective  
This project demonstrates the creation of a fully automated and secure **phishing campaign simulation platform** using AWS. It aims to educate organizations and individuals on social engineering threats by providing hands-on experience in identifying, analyzing, and mitigating phishing attacks within a controlled and ethical environment.

---

## Skills Learned  

### Cloud Infrastructure  
- Deploying and managing AWS services (e.g., EC2).  
- Configuring IAM roles, VPCs, and security groups.  
- Utilizing tools like AWS Shield and WAF for protection.  

### Cybersecurity  
- Understanding phishing techniques and their countermeasures.  
- Simulating social engineering attacks in a responsible manner.  

---

## Services Used  
- **AWS**  
- **EC2**  
- **VPC**  
- **GoPhish**  

---

## Steps  

1. **Download GoPhish Simulator**  
   - Access the GoPhish Simulator from the Amazon Marketplace.  
   ![GoPhish Simulator](https://github.com/user-attachments/assets/6e156195-a85b-43ac-8331-22add031dc9e)  

2. **Create a VPC**  
   - Set up a Virtual Private Cloud (VPC).  
   ![Create VPC](https://github.com/user-attachments/assets/6ac653e9-72f7-44fc-bf05-3f4ad1dc704e)  

3. **Choose a Public Subnet**  
   - Select the public subnet created within the VPC.  
   ![Public Subnet](https://github.com/user-attachments/assets/98869712-9717-43fa-9a89-5feed3e12fe9)  

4. **Enable Auto-Assign Public IPv4 Address**  
   - Allow automatic assignment of public IPv4 addresses.  
   ![Enable IPv4](https://github.com/user-attachments/assets/12e39780-eebb-4501-9bca-976f5ef024e5)  

5. **Create a Key Pair**  
   - Generate a key pair for secure instance access.  
   ![Create Key Pair](https://github.com/user-attachments/assets/0642e5d4-e562-4889-a616-cb052b84b614)  

6. **Create a Security Group**  
   - Configure security group rules to allow necessary traffic.  
   ![Create Security Group](https://github.com/user-attachments/assets/8450d206-8044-411d-b200-4ac9fc19e08c)  

7. **Launch the Instance**  
   - Deploy the instance for running the GoPhish platform.  
   ![Launch Instance](https://github.com/user-attachments/assets/5e61f75d-8c3f-433d-9afa-5d3e8926a1bc)  

8. **Wait for Initialization**  
   - Allow the instance to fully initialize before proceeding.  
   ![Instance Initialization](https://github.com/user-attachments/assets/79b4f23c-1819-443b-b447-409117974db4)  

9. **Access the Sign-In Page**  
   - Use the instance's public address in a web browser to reach the GoPhish sign-in page.  
   ![Sign-In Page](https://github.com/user-attachments/assets/2ebbeaa3-4f15-45fd-a82e-33481b997a33)  

10. **Log In**  
    - Log in using the instance ID as the password.  
<img width="495" alt="image" src="https://github.com/user-attachments/assets/e06ca631-c7fa-4477-b4e2-fae505ff5d61">

11. **Create Phishing Campaigns**  
    - Use the platform to create phishing campaigns for specific users and groups.  
    ![Users and Groups](https://github.com/user-attachments/assets/7fa2f599-20af-4d8d-836d-d5600b19b590)  

---

This step-by-step guide provides a clear and systematic approach to setting up a phishing campaign simulation while leveraging AWS infrastructure.


























