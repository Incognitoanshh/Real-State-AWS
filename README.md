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

Authentication is powered by **AWS Cognito** using Amplify CLI and hosted UI.  
It supports:
- User sign-up and sign-in
- JWT-based session management
- Secure APIs with token verification

---

## 🗂️ Project Structure

```bash
├── client/              # Next.js frontend with Tailwind, Shadcn UI, Mapbox
├── server/              # Node.js Express backend with Prisma, Auth, API logic
├── prisma/              # Prisma schema and migration scripts
├── scripts/             # AWS deployment scripts (EC2 setup, RDS config)
├── public/              # Static assets
├── README.md            # Project documentation
```

---

## 🚀 Deployment

This project is deployable on AWS using EC2 for backend and S3 + CloudFront for frontend.

- 🖥️ **Backend**: Deployed on **EC2** with Node.js + PostgreSQL (RDS)
- 🌐 **Frontend**: Hosted on **S3**, optionally via **Vercel**
- 🌍 **DNS**: Managed by **Route 53**
- 🔐 **Authentication**: Managed by **AWS Cognito**

---

## 📎 Resources and Links

### Code & Assets:
- ⭐ Completed Code
- ⭐ Diagrams
- ⭐ UI Assets
- ⭐ AWS EC2 Setup Guide

### Documentation:
- 📌 [Mapbox Docs](https://docs.mapbox.com/)
- 📌 [Shadcn UI Docs](https://ui.shadcn.com/)
- 📌 [Zod Docs](https://zod.dev/)
- 📌 [React Hook Form](https://react-hook-form.com/)
- 📌 [Prisma Docs](https://www.prisma.io/docs)
- 📌 [AWS CLI Docs](https://docs.aws.amazon.com/cli/)
- 📌 [Amplify CLI](https://docs.amplify.aws/)
- 📌 [AWS Billing Console](https://console.aws.amazon.com/billing/)

---

## ✍️ Author

Made with 💻 and ☁️ by [Incognitoanshh]

