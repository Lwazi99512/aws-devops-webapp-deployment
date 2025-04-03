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
