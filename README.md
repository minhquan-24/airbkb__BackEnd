<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>
<a href="https://circleci.com/gh/nestjs/nest" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>
<a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
<a href="https://opencollective.com/nest#backer" target="_blank"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="https://opencollective.com/nest#sponsor" target="_blank"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
  <a href="https://paypal.me/kamilmysliwiec" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg" alt="Donate us"/></a>
    <a href="https://opencollective.com/nest#sponsor"  target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>
  <a href="https://twitter.com/nestframework" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow" alt="Follow us on Twitter"></a>
</p>
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->

## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

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