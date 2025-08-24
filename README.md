# Serverless Website Project 🚀

This project is a **serverless website** hosted on **AWS S3** with backend functionality using **AWS Lambda, API Gateway, and DynamoDB**.  
It demonstrates how to build and deploy a website without managing servers, using serverless cloud computing architecture.

---

## 📌 Features
- **Static Frontend** (HTML, CSS, JavaScript) hosted on Amazon S3  
- **Contact Form** connected to AWS Lambda via API Gateway  
- **DynamoDB Integration** for storing submitted form data  
- **CORS Enabled** for cross-domain API requests  
- **Scalable & Pay-as-you-go** architecture  

---

## 🛠️ Tech Stack
- **Frontend**: HTML5, CSS3, JavaScript  
- **Backend**: AWS Lambda (Node.js 18.x)  
- **Database**: Amazon DynamoDB  
- **Hosting**: Amazon S3 (Static Website Hosting)  
- **API**: Amazon API Gateway  

---

## 📂 Project Structure
project-root/
│── index.html # Home page
│── about.html # About page
│── contact.html # Contact page (form submission)
│── style.css # Styles for all pages
│── README.md # Project documentation



---

## 🚀 Deployment Steps
1. **Create S3 Bucket** → Enable static website hosting → Upload files (`index.html`, `about.html`, `contact.html`, `style.css`).  
2. **Create DynamoDB Table**  
   - Table Name: `ContactForm`  
   - Primary Key: `id` (String)  
3. **Create Lambda Function** → Handles form submission and saves data into DynamoDB.  
4. **Create API Gateway**  
   - Route: `POST /submit`  
   - Integration: Lambda Function  
   - Enable **CORS**  
5. **Update `contact.html`** with API Gateway endpoint.  
6. **Test the form** → Submitted data should appear in DynamoDB.  

---

## 📸 Screenshots
(

<img width="1596" height="862" alt="image" src="https://github.com/user-attachments/assets/236deec4-d63e-459b-aaaa-1e9f6d0c10ef" />,
<img width="1597" height="809" alt="image" src="https://github.com/user-attachments/assets/acffb507-184a-4f13-909b-c333449074de" />,
<img width="1599" height="812" alt="image" src="https://github.com/user-attachments/assets/d27b6fbe-b4fd-4bc3-ba9e-c18510437a62" />,
<img width="1595" height="809" alt="image" src="https://github.com/user-attachments/assets/70d09741-d673-4e2a-8273-1acd11302c7f" />,
<img width="1595" height="814" alt="image" src="https://github.com/user-attachments/assets/7de3eaae-f611-4166-93fa-89ac706c8e2d" />

)

---

## 🌐 Live Demo
- **S3 Website URL**: _(http://my-serverless-website-bucket11.s3-website-us-east-1.amazonaws.com/)_  

---

## 👨‍💻 Author
Developed by **Badarqa Shakoor**  
