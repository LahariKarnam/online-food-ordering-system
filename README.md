🍔 CloudBites – Serverless Food Ordering Web Application
CloudBites is a fully serverless, scalable, and cost-effective food ordering platform powered by AWS. Built using React.js and AWS services like Lambda, DynamoDB, Cognito, S3, and Amplify, the app offers real-time ordering, role-based access, secure payments, and a clean UI/UX experience.

🔧 Tech Stack
Layer	Technology Used
Frontend	React.js, AWS Amplify
Authentication	AWS Cognito
Backend	AWS Lambda + API Gateway
Database	Amazon DynamoDB
Media Storage	Amazon S3
Notifications	AWS SNS
DevOps	GitHub CI/CD via AWS Amplify
⚙️ Architecture Flow
User accesses the React frontend hosted via Amplify.
Authentication is handled via Amazon Cognito.
API Gateway routes user requests to Lambda functions.
Lambda performs backend logic and interacts with DynamoDB.
S3 stores images and receipts, while SNS sends real-time notifications.
🚀 Features
✅ Serverless deployment (no infrastructure management)
✅ Role-based access for users and admins
✅ Real-time order tracking via SNS
✅ Secure login with MFA support
✅ Responsive UI using React
📦 Setup Instructions
Prerequisites
Node.js, AWS CLI, Amplify CLI, Git
