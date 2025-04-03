# NextWork Web App: AWS EC2 + VS Code Deployment  
A Java-based web app deployed on AWS EC2 using Maven, VS Code Remote-SSH, and Linux.  

## 🛠️ Tech Stack  
- **AWS**: EC2 (Amazon Linux 2023), Key Pairs, IPv4 DNS  
- **Tools**: VS Code (Remote-SSH extension), Apache Maven  
- **Languages**: Java, HTML/JSP  

## 🚀 Setup Steps  
1. Launched EC2 instance & configured SSH access  
2. Installed Java, Maven, and VS Code remotely  
3. Generated web app using `mvn archetype:generate`  
4. Edited `index.jsp` for dynamic content:  
   ```html
   <h2>Hello Lwazi!</h2>
   <p>This is my NextWork web application working!</p>
## 🔍 Key Takeaways & Lessons Learned

### **Technical Insights**
- **Linux Dominance**: AWS EC2 works natively with Linux (Amazon Linux 2023) - my Windows setup failed initially  
- **SSH Keys Are Golden**: `chmod 400 your-key.pem` solves 80% of connection issues  
- **VS Code Magic**: Remote-SSH extension lets you edit cloud files like local ones  
### **Process Wins**
- Maven archetypes (`mvn archetype:generate`) automate Java project scaffolding  
- EC2’s IPv4 DNS is your cloud "street address" for connections  

### **What I’d Do Differently**
- Automate dependency checks earlier with `mvn dependency:analyze`  
- Use AWS CloudShell for faster CLI access
- 📄 [Full Project Report](./legendary-aws-devops-vscode.pdf)
- ## 🚀 Quick Start  
1. Clone repo  
2. `ssh -i key.pem ec2-user@your-ec2-ip`  
3. Open in VS Code with Remote-SSH  
