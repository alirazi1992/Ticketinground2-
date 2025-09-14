# Ticketinground2 🎫

A modern, Farsi (RTL)-first IT support ticketing dashboard built with **Next.js**, **Tailwind CSS**, and **TypeScript** using **Clean Architecture**.  
Includes a multi-role system (**Client**, **Admin**, **Technician**) for tracking, managing, and replying to support requests in real time.

---

## 📑 Table of Contents

1. [Features](#-features)  
2. [Tech Stack](#-tech-stack)  
3. [Getting Started](#-getting-started)  
   - [Prerequisites](#prerequisites)  
   - [Installation](#installation)  
   - [Environment Variables](#environment-variables)  
   - [Running Locally](#running-locally)  
4. [Architecture](#-architecture)  
5. [Usage](#-usage)  
6. [Roadmap](#-roadmap)  
7. [Contributing](#-contributing)  
8. [License](#-license)  

---

## ✨ Features

- Multi-step **ticket creation** (with dynamic categories & subcategories)  
- Full **RTL (Farsi)** UI support  
- **Role-based dashboards**: Client / Admin / Technician  
- Technician **reply & messaging** system  
- Admin **ticket assignment & management**  
- **Dark / Light mode** toggle  
- **Farsi / English language switching**  
- Secure form handling & validation with **Yup**  
- Fully responsive, **mobile-friendly UI**  
- Modern **glassmorphism design**  
- **WebSocket-ready** for real-time updates  

---

## 🛠 Tech Stack

- **Framework**: [Next.js](https://nextjs.org/) (v14+)  
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)  
- **Language**: TypeScript  
- **Architecture**: Clean Architecture  
- **Forms**: React Hook Form + Yup  

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or newer recommended)  
- npm / pnpm / yarn  
- (Optional) Docker & docker-compose  

---

### Installation

```bash
# Clone repository
git clone https://github.com/alirazi1992/Ticketinground2-.git
cd Ticketinground2-

# Install dependencies
npm install
# or
pnpm install
# or
yarn install
