[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=43&pause=1000&random=false&width=500&height=70&lines=Next-like-amazon)](https://git.io/typing-svg)



# Build Full-ECommerce By Next.js 13+, App Router, Server Components and Actions

|                |                                                        |
| -------------- | ------------------------------------------------------ |
| Tech           | Nextjs 13+, Server Components & Actions, Route Handler |
| UI             | Tailwind, DaisyUI, Chart.js                            |
| Database       | MongoDB, Mongoose                                      |
| Payment        | PayPal, Stripe                                         |
| Deployment     | Github, Vercel, MongoDB Atlas                          |
| Authentication | Auth.js, Google Auth                                   |
| Others         | Cloudinary, Zustand, SWR                               |


## Run Locally

1.Create .env File

   - duplicate .env.example and rename it to .env

2.Setup MongoDB

   - Local MongoDB
     - Install it from [here](https://www.mongodb.com/try/download/community)
     - In .env file update MONGODB_URI=mongodb://localhost/amazona
   - OR Atlas Cloud MongoDB
     - Create database at [https://cloud.mongodb.com](https://cloud.mongodb.com)
     - In .env file update MONGODB_URI=mongodb+srv://your-db-connection

3Install and Run

   ```shell
     npm install
     npm run dev
   ```

5. Seed Data

   - Run this on browser: http://localhost:3000/api/seed
   - It returns admin email and password and 6 sample products

6. Admin Login

   - Run http://localhost:3000/signin
   - Enter admin email "admin@example.com" and password "123456" and click Signin

   
