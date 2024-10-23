# **Static Website on Azure**

![Deploy Status](https://github.com/kneeble/staticwebsiteazure/actions/workflows/azure-static-web-apps-white-water-03e1a871e.yml/badge.svg)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  
![Hugo Version](https://img.shields.io/badge/Hugo-0.104.0-blue.svg)  
![Code Size](https://img.shields.io/github/languages/code-size/kneeble/staticwebsiteazure)  
![Last Commit](https://img.shields.io/github/last-commit/kneeble/staticwebsiteazure)

This repository contains a professional-grade static website built using **Hugo** and hosted on **Azure Web App**. Leveraging **GitHub Actions** for automated deployment, this project demonstrates skills in modern web development, CI/CD pipelines, and cloud hosting services. It showcases my ability to handle end-to-end web project deployment and management, making it an ideal example of my technical and DevOps skills for potential recruiters.

---

## **Key Features**

- **Fast Static Site Generation**: Built with Hugo for blazing-fast static site generation.
- **CI/CD with GitHub Actions**: Fully automated deployment to Azure Web App, integrating Continuous Integration and Continuous Deployment to streamline updates.
- **Cloud Hosting with Azure**: Hosted on Azure Web App, using industry-leading cloud services for scalability, reliability, and performance.
- **Optimized for Professional Use**: The site is designed with best practices in mind—clean, responsive, and easily extendable.

---

## **Skills Highlighted**

This project showcases a range of technical skills and concepts that are directly transferable to real-world DevOps, software development, and cloud engineering roles, including:

- **Version Control and Collaboration**: Leveraging GitHub to manage source code and enable team collaboration.
- **Infrastructure as Code**: Automated cloud deployments with GitHub Actions.
- **Web Development**: Experience with static site generation, HTML/CSS, and asset management.
- **Cloud Computing**: Hands-on experience with Azure services, including setting up, managing, and scaling cloud-based applications.
- **Continuous Deployment Pipelines**: Implementing CI/CD pipelines for smooth and reliable updates without manual intervention.

---

## **Technologies Used**

- **Hugo**: Fast, flexible, and modern static site generator.
- **Azure Web App**: Scalable cloud hosting with Azure.
- **GitHub Actions**: Automated workflows for building, testing, and deploying code.

---

## **Project Structure**

```bash
.
├── archetypes/       # Content archetypes for Hugo
├── content/          # Markdown files for pages and posts
│   ├── posts/        # Website posts
├── Resources/           # Resources for Website
├── themes/           # Theme used for the website
├── hugo.toml       # Hugo configuration file
└── ...
```
## **Live Demo**

Visit the **[Live Website](http://kalebneeble.com/)** hosted on Azure to see this project in action.

---

## **Getting Started Locally**

To run this project locally and explore the code:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/kneeble/staticwebsiteazure.git
   cd staticwebsiteazure
    ```
2. **Install hugo**:
[Hugo Install](https://hugo-docs.netlify.app/en/getting-started/quick-start/#:~:text=Quick%20Start%201%20Step%201%3A%20Install%20Hugo%20Homebrew%2C,...%206%20Step%206%3A%20Customize%20the%20Theme%20)

3. **Run local server**:
    ```bash
    hugo server
    ```
   **Visit ```http://localhost:1313``` to view the site locally.**


## **Deployment Pipeline**

This project utilizes **GitHub Actions** for Continuous Integration and Continuous Deployment. When a push is made to the `main` branch, the following process is triggered:

1. **Build**: Hugo compiles the static site from markdown files.
2. **Test**: Optional testing steps can be integrated here.
3. **Deploy**: The site is automatically deployed to Azure Web App.

### **Manual Deployment**

1. **Generate static files**:

   ```bash
   hugo
   ```
2. **Upload to Azure**: Use the Azure CLI or FTP to upload the generated files in the ```public/``` folder.

## **Contact Me**

**GitHub**: [github.com/kneeble](https://github.com/kneeble)  
**LinkedIn**: [linkedin.com/in/kaleb-neeble](https://linkedin.com/in/kaleb-neeble)

## **License**

This project is licensed under the MIT License. You can find the full text of the license in the [LICENSE](LICENSE) file.




   






