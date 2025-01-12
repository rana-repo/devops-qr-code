# devops-qr-code

Here’s a polished and professional version of your README for the GitHub repository:  

---

# ** QR Code Generator**  

This repository contains the **DevOps Capstone Project**, a sample application that generates QR codes for user-provided URLs. The project showcases the implementation of **DevOps best practices**, including **containerization**, **CI/CD pipelines**, and **monitoring**.  

## **Overview**  
- **Front-End**: Built with [Next.js](https://nextjs.org/), the web application allows users to submit URLs.  
- **API**: Developed using [FastAPI](https://fastapi.tiangolo.com/), the back-end generates QR codes and uploads them to an **AWS S3 bucket**.  

---

## **Features**  
- Submit URLs via the front-end web application.  
- Generate and retrieve QR codes via the FastAPI-based back-end.  
- Store QR codes securely in **AWS S3**.  
- Hands-on demonstration of DevOps principles like containerization, CI/CD, and monitoring.  

---

## **Getting Started**  

### **1. Running the API Locally**  
The API code is located in the `api` directory.  

#### **Steps**:  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/<your-username>/devops-qr-code.git  
   cd devops-qr-code/api  
   ```  

2. Set up a Python virtual environment:  
   ```bash  
   python -m venv .venv  
   source .venv/bin/activate  # For Windows: .venv\Scripts\activate  
   ```  

3. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

4. Configure environment variables:  
   - Create a `.env` file based on `.env.example`.  
   - Add your **AWS Access Key**, **Secret Key**, and **S3 Bucket Name**.  

5. Run the API server:  
   ```bash  
   uvicorn main:app --reload  
   ```  

Your API server will be running at: [http://localhost:8000](http://localhost:8000).  

---

### **2. Running the Front-End Locally**  
The front-end code is located in the `front-end-nextjs` directory.  

#### **Steps**:  
1. Navigate to the front-end directory:  
   ```bash  
   cd ../front-end-nextjs  
   ```  

2. Install dependencies:  
   ```bash  
   npm install  
   ```  

3. Start the Next.js server:  
   ```bash  
   npm run dev  
   ```  

Your front-end application will be running at: [http://localhost:3000](http://localhost:3000).  


---

## **Contributing**  
Contributions are welcome! Please follow these steps:  
1. Fork the repository.  
2. Create a feature branch: `git checkout -b feature-name`.  
3. Commit your changes: `git commit -m "Description of changes"`.  
4. Push to your branch: `git push origin feature-name`.  
5. Open a pull request.  

---
