# 🏠 Scalable Real Estate Application

Build a **Rental Apartment Platform** using **Next.js**, **Node.js**, and **AWS**. This project demonstrates a fully functional, enterprise-grade full-stack real estate web application integrated with modern technologies, AWS services, and best practices.

---

## ✨ Features

- Full-stack architecture using **Next.js** and **Node.js**
- Authentication with **AWS Cognito**
- Dynamic frontend with **Shadcn UI**, **Tailwind CSS**, and **Framer Motion**
- Backend integration with **EC2**, **RDS**, **S3**, and **API Gateway**
- Form handling with **React Hook Form** and **Zod** validation
- State management using **Redux Toolkit**
- Type-safe codebase using **TypeScript**
- PostGIS integration for geospatial features
- Map visualization using **Mapbox GL**

---

## 🧰 Tech Stack

### Frontend:
- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Shadcn UI](https://ui.shadcn.com/)
- [Framer Motion](https://www.framer.com/motion/)
- [TypeScript](https://www.typescriptlang.org/)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [Redux Toolkit Query](https://redux-toolkit.js.org/rtk-query/overview)
- [Zod](https://zod.dev)
- [React Hook Form](https://react-hook-form.com/)
- [Mapbox GL](https://docs.mapbox.com/mapbox-gl-js/guides/)

### Backend:
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [PostgreSQL](https://www.postgresql.org/)
- [PostGIS](https://postgis.net/)
- [Prisma ORM](https://www.prisma.io/)
- [AWS EC2](https://aws.amazon.com/ec2/)
- [AWS RDS](https://aws.amazon.com/rds/)
- [AWS S3](https://aws.amazon.com/s3/)
- [AWS API Gateway](https://aws.amazon.com/api-gateway/)
- [AWS Cognito](https://aws.amazon.com/cognito/)
- [AWS Amplify](https://docs.amplify.aws/)
- [Postman](https://www.postman.com/)

---

## 🔐 Authentication

Authentication is powered by **AWS Cognito** using Amplify CLI and hosted UI. It supports user sign-up, sign-in, and secure session handling with JWT tokens.

---

## 🗂️ Project Structure

```bash
├── client/              # Next.js frontend with Tailwind, Shadcn UI, Mapbox
├── server/              # Node.js Express backend with Prisma, Auth, API logic
├── prisma/              # Prisma schema and migration scripts
├── scripts/             # AWS deployment scripts (EC2 setup, RDS config)
├── public/              # Static assets
├── README.md



🚀 Deployment

This project is deployable on AWS using EC2 for backend hosting and S3 + CloudFront for frontend.
	•	Backend runs on EC2 with Node.js + PostgreSQL (RDS)
	•	Frontend deployed via S3 (or Vercel for ease)
	•	Use Route 53 for DNS and Cognito for user pool management

Resources and Links

Code & Assets
	•	⭐ Completed Code
	•	⭐ Diagrams
	•	⭐ Assets
	•	⭐ AWS EC2 Instructions

Documentation
	•	📌 Mapbox
	•	📌 Shadcn
	•	📌 Zod
	•	📌 React Hook Form
	•	📌 Prisma Docs
	•	📌 AWS CLI
	•	📌 Amplify
	•	📌 AWS Billing Console

