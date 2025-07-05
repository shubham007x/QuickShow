
# Quickshow 🎭

Quickshow is a full-stack application for booking and managing movie or show tickets. It includes user authentication, seat selection, admin management, and real-time availability updates.

## 🛠 Tech Stack

**Frontend:**
- React.js
- Tailwind CSS
- Redux Toolkit
- React Router

**Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose)
- Clerk (Authentication)
- Inngest (Event-driven architecture)

**Other Tools:**
- Vercel (Frontend Deployment)
- Render / Railway (Backend Deployment)
- Git & GitHub
- BFG Repo Cleaner (Secret Cleanup)
- GitHub Push Protection

---

## 🚀 Features

- 🎟️ User seat booking system with real-time availability
- 🔐 Secure user authentication with Clerk
- 🧑‍💼 Admin panel for managing shows, seats, and bookings
- 📅 View show timings with ISO-formatting
- 🖼️ Movie poster and details integration
- ⚙️ Context API and Redux Toolkit for global state management
- 🌈 Custom animations and gradients

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/quickshow.git
   cd quickshow
   ```

2. **Install dependencies for server and client**
   ```bash
   # Server
   cd server
   npm install

   # Client
   cd ../client
   npm install
   ```

3. **Environment Variables**

   Create `.env` files in both `/server` and `/client` directories. Sample for server:
   ```env
   MONGO_URI=your_mongo_uri
   CLERK_SECRET_KEY=your_clerk_secret
   INNGEST_EVENT_KEY=your_inngest_key
   ```

4. **Start development servers**
   ```bash
   # Server
   cd server
   npm run dev

   # Client
   cd ../client
   npm run dev
   ```

---

## 🌐 Deployment

- **Frontend:** [Vercel](https://vercel.com)
- **Backend:** [Render](https://render.com) or [Railway](https://railway.app)
- **Environment Variables** should be added to deployment dashboards

---

## 📁 Folder Structure

```
quickshow/
├── client/         # React frontend
├── server/         # Node/Express backend
├── .env            # Environment variables
├── README.md
```

---


## 🙋‍♂️ Author

**Shubham Agdari**  
[LinkedIn](https://www.linkedin.com/in/shubham-agdari/) • [GitHub](https://github.com/shubhamagdari)

---

## 📝 License

This project is licensed under the MIT License.
