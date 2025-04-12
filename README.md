# 🍔 CloudBites – Serverless Food Ordering Web Application

CloudBites is a fully serverless, scalable, and cost-effective food ordering platform powered by AWS. Built using React.js and AWS services like Lambda, DynamoDB, Cognito, S3, and Amplify, the app offers real-time ordering, role-based access, secure payments, and a clean UI/UX experience.

---

## 📸 Demo


## 🔧 Tech Stack

| Layer           | Technology Used                          |
|----------------|-------------------------------------------|
| Frontend       | React.js, AWS Amplify                     |
| Authentication | AWS Cognito                               |
| Backend        | AWS Lambda + API Gateway                  |
| Database       | Amazon DynamoDB                           |
| Media Storage  | Amazon S3                                  |                       |
| DevOps         | GitHub CI/CD via AWS Amplify              |

---

## ⚙️ Architecture Flow

1. User accesses the React frontend hosted via Amplify.
2. Authentication is handled via Amazon Cognito.
3. API Gateway routes user requests to Lambda functions.
4. Lambda performs backend logic and interacts with DynamoDB.
5. S3 stores images and receipts, while SNS sends real-time notifications.

---

## 🚀 Features

- ✅ Serverless deployment (no infrastructure management)
- ✅ Role-based access for users and admins
- ✅ Real-time order tracking via SNS
- ✅ Secure login with MFA support
- ✅ Responsive UI using React 

---

## 📦 Setup Instructions

### Prerequisites
- Node.js, AWS CLI, Amplify CLI, Git

### Steps

# Install dependencies
npm install

# Configure Amplify
amplify init
amplify push

# Start the app
npm start
