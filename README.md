
## Description

## Project setup
# 🏡 AirBKB - Booking Platform (Fullstack)

```bash
$ npm install
A fullstack web application inspired by Airbnb, allowing users to browse, book, and manage rental properties.

---

# 🧩 System Architecture

```text
Frontend (Next.js)
        ↓
 REST API (Backend - Nest.js)
        ↓
   Database (SQL)
```

## Compile and run the project
- Frontend handles UI/UX and user interactions  
- Backend handles API, authentication, and business logic  
- Database stores users, listings, bookings, and reviews  

```bash
# development
$ npm run start
---

# watch mode
$ npm run start:dev
# 🚀 Features

# production mode
$ npm run start:prod
```
## 🖥️ Frontend
- Browse and search listings  
- View listing details  
- Booking interface  
- Authentication (Login/Register)  

## Run tests
---

```bash
# unit tests
$ npm run test
## ⚙️ Backend
- RESTful API  
- Authentication & authorization  
- Listing management (CRUD)  
- Booking system  
- Role-based access (Host / Guest)  

# e2e tests
$ npm run test:e2e
---

# test coverage
$ npm run test:cov
```
# 🛠️ Tech Stack

## 🎨 Frontend
- Next.js  
- TailwindCSS  

## ⚙️ Backend
- Nest.js  
 
## 🗄️ Database
- SQL  

---

## Deployment
# 🔗 API Overview

When you're ready to deploy your NestJS application to production, there are some key steps you can take to ensure it runs as efficiently as possible. Check out the [deployment documentation](https://docs.nestjs.com/deployment) for more information.
| Method | Endpoint        | Description        |
|--------|---------------|--------------------|
| POST   | /auth/login    | Login user         |
| POST   | /auth/register | Register user      |
| GET    | /listings      | Get listings       |
| POST   | /bookings      | Create booking     |

If you are looking for a cloud-based platform to deploy your NestJS application, check out [Mau](https://mau.nestjs.com), our official platform for deploying NestJS applications on AWS. Mau makes deployment straightforward and fast, requiring just a few simple steps:
---

# ⚙️ Installation

## 1. Clone project

```bash
$ npm install -g @nestjs/mau
$ mau deploy
git clone https://github.com/tantailuong099-cloud/airbkb__FrontEnd.git
git clone https://github.com/tantailuong099-cloud/airbkb__BackEnd.git
```

With Mau, you can deploy your application in just a few clicks, allowing you to focus on building features rather than managing infrastructure.
---

## 2. Setup Backend

```bash
cd airbkb__BackEnd
npm install
npm start
```

---

## 3. Setup Frontend

```bash
cd airbkb__FrontEnd
npm install
npm start
```

## Resources
---

Check out a few resources that may come in handy when working with NestJS:
# 🔄 Data Flow

- Visit the [NestJS Documentation](https://docs.nestjs.com) to learn more about the framework.
- For questions and support, please visit our [Discord channel](https://discord.gg/G7Qnnhy).
- To dive deeper and get more hands-on experience, check out our official video [courses](https://courses.nestjs.com/).
- Deploy your application to AWS with the help of [NestJS Mau](https://mau.nestjs.com) in just a few clicks.
- Visualize your application graph and interact with the NestJS application in real-time using [NestJS Devtools](https://devtools.nestjs.com).
- Need help with your project (part-time to full-time)? Check out our official [enterprise support](https://enterprise.nestjs.com).
- To stay in the loop and get updates, follow us on [X](https://x.com/nestframework) and [LinkedIn](https://linkedin.com/company/nestjs).
- Looking for a job, or have a job to offer? Check out our official [Jobs board](https://jobs.nestjs.com).
1. User interacts with UI  
2. Frontend sends request  
3. Backend processes  
4. Database returns data  
5. Frontend renders UI  

## Support
---

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).
# 👨‍💻 Author

## Stay in touch
- GitHub: https://github.com/minhquan-24  

- Author - [Kamil Myśliwiec](https://twitter.com/kammysliwiec)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)
---

## License
# ⭐ Support

Nest is [MIT licensed](https://github.com/nestjs/nest/blob/master/LICENSE).
Give this project a ⭐ if you like it!