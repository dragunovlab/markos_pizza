# MARKO’S PIZZA 🍕

**MARKO’S PIZZA** is a modern eCommerce platform for ordering pizza, built with **Next.js**, **TypeScript**, **Prisma**, and **YooKassa** integration for payments.  
Features include product filtering, authentication, and email notifications.

---

## 🍕 MARKO’S PIZZA — A Modern eCommerce Platform for Pizza Ordering

**MARKO’S PIZZA** is a stylish, technologically advanced, and user-friendly pizza ordering service.  
This project demonstrates full-stack development skills, advanced **Next.js 14** architecture, attention to **UX/UI design**, high-quality frontend, and full integration with payment and email services.

![Screenshot](./public/preview.png)

---

## 🔗 Figma Prototypes

👉 **View the design in Figma:**

- [Open prototype 1](https://www.figma.com/proto/Ny6HqEo3oFM1DXkWustwAH/Untitled?node-id=1-5&t=KL9RvtvoJxrKZRSU-1)  
- [Open prototype 2](https://www.figma.com/proto/Ny6HqEo3oFM1DXkWustwAH/Untitled?node-id=49-5&t=KL9RvtvoJxrKZRSU-1)  
- [Open prototype 3](https://www.figma.com/proto/Ny6HqEo3oFM1DXkWustwAH/Untitled?node-id=49-5&t=kIkprKrJMvc57gQQ-1)

---

## 🚀 Features

- ✅ **Server-side product filtering** with URL parameters  
- ✅ **Product view**, **add to cart**, **checkout**  
- ✅ **Authentication** via email/password, GitHub, Google  
- ✅ **Account confirmation** via email  
- ✅ **Profile editing** and **order history**  
- ✅ **Payment via YooKassa**  
- ✅ **Email notifications** (registration, order, payment) via Resend  
- ✅ **Parallel Routes support** (viewing product in a modal or a separate page)  
- ✅ **Real-world examples** of Client and Server components  
- ✅ **Deployment on Vercel**, PostgreSQL database  
- ✅ **Modern UX/UI design** and **microinteractions**

---

## 🎨 UX/UI Design

The project emphasizes **user experience**:

- Clean, minimalist UI using **TailwindCSS** + **ShadCN UI**
- Smooth animations and responses using `react-hot-toast` and `toploader`
- Easy navigation for **mobile** and **desktop** users
- **Intuitive purchase process**
- **Microinteractions** that make the interface feel "alive"

---

## 🛠 Technologies Used

| Technology                   | Purpose                                                  |
|-----------------------------|----------------------------------------------------------|
| **Next.js 14**              | App Router, Parallel Routes, Server Actions              |
| **TypeScript**              | Safe and scalable development                            |
| **TailwindCSS + ShadCN UI** | Fast styling and ready-made UI components                |
| **Prisma + PostgreSQL**     | ORM and database                                         |
| **NextAuth**                | Authentication and sessions                              |
| **React Hook Form + Zod**   | Forms and data validation                                |
| **Zustand**                 | Simple global state management                           |
| **Resend**                  | Email notifications                                      |
| **YooKassa**                | Online payments                                          |

> Also used: `lucide-react`, `react-use`, `react-hot-toast`, `react-insta-stories`, `nextjs-toploader`.

---

## 📸 Screenshots

### 🏠 Home Page  
<img src="./public/screenshot1.png" width="600" alt="Home page">

### 🍕 Product Page  
<img src="./public/screenshot2.png" width="600" alt="Product page">

---

## ⚙️ How to Run the Project

1. Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/markos-pizza.git
cd markos-pizza
npm install

2. Create a .env file based on .env.example and add your keys:

cp .env.example .env

3. Generate Prisma and set up the database:

npx prisma generate
npx prisma db push

4. Run the project:

npm run dev

5. Open the app in the browser at http://localhost:3000
