# 🍵 Get Me A Chai

**Get Me A Chai** is a modern, high-performance "Buy Me a Coffee" clone built for creators. It allows users to create personalized profile pages and test self-donation flows in a secure and interactive way. This project is built for learning, experimentation, and portfolio showcase.

🌐 **Live Demo:** [get-me-a-chai-hemant.vercel.app](https://get-me-a-chai-hemant.vercel.app/)
📂 **Repository:** [GitHub](https://github.com/TheHemantPandey/Get-Me-A-Chai)

![Get Me A Chai Banner](/tea.gif)

---

## 🚀 Features

* **GitHub Authentication** – One-click login with GitHub OAuth.
* **Creator Dashboards** – Instantly create personalized profile pages.
* **Self-Donation Flow** – Test donations and payments for practice.
* **Responsive UI/UX** – Dark theme, Glassmorphism design, smooth animations.
* **Modern Stack** – Built with the latest web technologies for optimal performance.

---

## 🛠 Tech Stack

* **Framework:** [Next.js 16 (App Router)](https://nextjs.org/)
* **Frontend:** [React 19](https://react.dev/), [Tailwind CSS 4](https://tailwindcss.com/)
* **Backend:** Node.js (API Routes & Server-Side Logic)
* **Database:** [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
* **Authentication:** [NextAuth.js](https://next-auth.js.org/)
* **State Management:** React Session Hooks
* **Assets:** Custom GIFs and SVG Icons

---

## 📦 Getting Started

### Prerequisites

* Node.js 18.x or later
* npm / yarn / pnpm

### Installation

1. **Clone the repository:**

```bash
git clone https://github.com/TheHemantPandey/Get-Me-A-Chai.git
cd Get-Me-A-Chai
```

2. **Install dependencies:**

```bash
npm install
```

3. **Set up environment variables:**
   Create a `.env.local` file in the root folder:

```env
NEXT_PUBLIC_URL=http://localhost:3000
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your_secret_key

# Database
MONGODB_URI=your_mongodb_connection_string

# OAuth Providers
GITHUB_ID=your_github_id
GITHUB_SECRET=your_github_secret
```

4. **Run the development server:**

```bash
npm run dev
```

---

## ⚙️ How It Works

1. **Secure Login:** Users authenticate via GitHub OAuth.
2. **Profile Setup:** Creators fill in their profile details on their dashboard.
3. **Practice Page:** A personalized page is generated in Account/Payments.
4. **Self-Donation:** Users can simulate donations to test the flow.

> Future plans include transforming this project into a full crowdfunding platform with cross-user support.

---

## 📸 Screenshots

|        Setup Profile       |      Test Donations      |
| :------------------------: | :----------------------: |
| ![Fund Yourself](<img width="1350" height="717" alt="image" src="https://github.com/user-attachments/assets/bfa4249c-3c45-4e76-b2b0-c0993fae2cf9" />
) | ![Community](<img width="1364" height="722" alt="image" src="https://github.com/user-attachments/assets/d4f4f730-6a2c-4bb6-b42d-4b938640ff63" />
) |

---

## 🤝 Contributing

Contributions are welcome! To help expand this project:

1. Fork the repository.
2. Create a feature branch.
3. Submit a pull request.

---

Built with ❤️ by **Hemant Pandey** for creators everywhere.
