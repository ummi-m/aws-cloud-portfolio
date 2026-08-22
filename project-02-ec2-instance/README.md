# Project 02 – Amazon EC2 Instance

## 📌 Objective

To create and connect to an Amazon EC2 virtual machine using the AWS Management Console.

## ☁️ AWS Service Used

- Amazon EC2
- Amazon VPC
- Security Groups
- EC2 Instance Connect

## ⚙️ Configuration

| Setting | Configuration |
|---|---|
| Instance Name | aws-cloud-project-02 |
| Operating System | Amazon Linux 2023 |
| Instance Type | t3.micro |
| Architecture | 64-bit (x86) |
| Storage | 8 GiB gp3 |
| Public IPv4 | Enabled |
| Security Group | launch-wizard-2 |
| SSH Port | 22 |
| Connection Method | EC2 Instance Connect |

## 🔐 Security Configuration

SSH access was configured through a Security Group.

- SSH – Port 22
- Access restricted to the required source
- HTTP – Port 80

## 🔗 Connection

The instance was successfully accessed using:

**EC2 Instance Connect → Connect using Public IP**

The Amazon Linux 2023 terminal was successfully opened.

## 🛠️ Troubleshooting

Initially, the EC2 Instance Connect connection failed.

The issue was investigated by checking:

- Public IPv4 address
- Security Group
- SSH inbound rule
- EC2 Instance Connect access

After correcting the security configuration, the instance was successfully connected.

## 🎯 Outcome

Successfully created and connected to an Amazon EC2 instance using the AWS Management Console.

## 📚 Skills Demonstrated

- Amazon EC2
- Virtual machines
- Security Groups
- SSH
- EC2 Instance Connect
- Public IP configuration
- Basic AWS networking
- AWS troubleshooting

  ## 💻 Successful EC2 Connection

The EC2 instance was successfully accessed using EC2 Instance Connect.

### Output

- Operating System: Amazon Linux 2023 )
- Logged-in user: ec2-user
- Hostname: ip-172-31-37-25.ap-south-2.compute.internal

![Successful EC2 Connection]
(EC2 instance connected.PNG)
