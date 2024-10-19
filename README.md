# SOC Analyst Home Lab

## Objective

In this project, the goal was to create a Security Operations Center (SOC) environment to better understand how to detect and respond to cybersecurity threats. I set up Windows servers to act as both target machines for my attack simulations and as hosts for services like Elastic, Kibana and Mythic C2. I then used Kali Linux to simulate attacks and integrated an OS ticketing system to generate tickets when alerts were triggered. By doing this, I was able to gain hands-on experience in network security monitoring, penetration testing and SOC operations.

### Skills Learned

- Practical experience deploying a SIEM platform.
- Detecting brute-force attacks through SSH and RDP.
- Experience simulating attacks using Kali Linux, including RDP attacks on target machines.
- Analysing logs, creating custom dashboards, and setting up security alerts.
- Setting up a C2 platform and creating payloads.
- Experience with using an OS ticketing system for tracking elastic alerts.

### Tools Used

- Vultr for hosting the virtual machines.
- ElasticSearch & Kibana for recording events, setting up alerts and dashboard creation.
- Windows servers for hosting ELK, Mythic C2, and acting as target machines.
- Mythic C2 and Apollo for simulating advanced threats.
- OS Ticketing system integrated with ElasticSearch for managing and tracking alerts.
- Kali Linux for simulating attacks on target machines using RDP and brute force.

## Key Steps
These are the most important steps and results that I collected throughout this projects.

#### Ref 1: Vultr Virtual Machines

![vultr](https://github.com/user-attachments/assets/d6e04002-b114-4600-a8f0-a04d05665c95)




#### Ref 2: Vultr Firewall Settings

<img width="452" alt="Picture1" src="https://github.com/user-attachments/assets/0e5e6d2a-ef83-401d-91a5-9a7ea943bad2">




#### Ref 3: Vultr VPN 2.0

<img width="452" alt="Picture2" src="https://github.com/user-attachments/assets/ef63912c-c6a4-402c-8171-110103149bf6">




#### Ref 4: VirtualBox Kali

<img width="452" alt="Picture17" src="https://github.com/user-attachments/assets/36872d28-1968-4d22-8e32-1295571ebb4d">




#### Ref 5: Sysmon on Windows Target 

![Picture20](https://github.com/user-attachments/assets/bd8c85ef-7c3d-4ece-8031-2461559146fc)





#### Ref 6: Elastic Agent installed

<img width="452" alt="Picture19" src="https://github.com/user-attachments/assets/027cb3d4-ce30-458e-ac54-f55b5cdfe9fc">




#### Ref 7: Elastic Activity

<img width="452" alt="Picture21" src="https://github.com/user-attachments/assets/8d75f348-9c4e-4328-911c-ee5a1f37e441">





#### Ref 8: Elastic/Kibana Dashboard

![Picture4](https://github.com/user-attachments/assets/829011fd-4a24-4db5-9c39-845d5a8d36db)





#### Ref 9: Elastic Alerts

<img width="452" alt="Picture25" src="https://github.com/user-attachments/assets/556a160a-c821-478b-beb2-ec53e53ce44e">





#### Ref 10: Kali RDP 

![Picture16](https://github.com/user-attachments/assets/d85cde4b-54b6-441d-bab1-bbfdce8b6e16)





#### Ref 11: Kali Brute Force

![Picture18](https://github.com/user-attachments/assets/8c407d9b-9797-48dd-b250-71d1c555edfa)





#### Ref 12: Mythic SetUp

![Picture22](https://github.com/user-attachments/assets/67bb565d-8d34-4708-aef2-2fc4e98c2bee)





#### Ref 13: Mythic Setup

<img width="452" alt="Picture24" src="https://github.com/user-attachments/assets/631a189a-5257-4366-98bc-e43ba5cb2a16">





#### Ref 14: Mythic Payload 

<img width="452" alt="Picture7" src="https://github.com/user-attachments/assets/c94cd8a2-9d3c-44f1-a084-f1c8ab740af6">





#### Ref 15: Elastic/Kibana Dashboards

![Picture10](https://github.com/user-attachments/assets/0c338cac-cafb-4128-86c6-f0f42a450aec)

<img width="452" alt="Picture11" src="https://github.com/user-attachments/assets/06862cc3-d865-491b-88fd-af6f8a289a95">





#### Ref 16: OsTicket Setup

<img width="452" alt="Picture8" src="https://github.com/user-attachments/assets/d9ca8f6a-d83a-4b2b-b0f7-524c24fb2f0e">





![Picture14](https://github.com/user-attachments/assets/9508339a-8de2-47b4-8d5d-7f9b45117f1e)






#### Ref 17: OsTicket Integration

<img width="452" alt="Picture23" src="https://github.com/user-attachments/assets/730f72d0-d35c-4c0f-b29a-b0aa703058b4">





#### Ref 18: IP investigation

![Picture12](https://github.com/user-attachments/assets/2b6c3f19-b57a-4917-b216-afb286e699c8)


<img width="452" alt="Picture13" src="https://github.com/user-attachments/assets/3ecdc719-af62-468e-9af0-7bc93c875347">




