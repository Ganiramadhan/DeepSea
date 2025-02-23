# 🌊 **DeepSea**

**DeepSea** is an **AI-powered management dashboard** designed to assist fishermen in detecting marine animals such as **fish, crabs, and shrimp** based on their behavioral patterns. The application provides an **interactive map** and **potential coordinates**, helping fishermen optimize their catches more efficiently.

## 🚀 **Tech Stack**

🔹 **Frontend:** Next.js (React Framework)\
🔹 **Backend:** NestJS (Node.js Framework)\
🔹 **Database:** PostgreSQL (via Docker)\
🔹 **Machine Learning:** Python *(Coming Soon 🚧)*\
🔹 **Containerization:** Docker & Docker Compose

## 🔥 **Features**

✅ **Interactive Dashboard** – Displays **map & coordinates** of potential marine animal locations\
✅ **Real-time Data** – Stores and manages detection records\
✅ **User Management** – Admin panel for managing user access\
✅ **Future AI Integration** – Machine Learning will enhance detection accuracy 🐟

## 📚 **Project Structure**

```
DeepSea/
│── frontend/         # Next.js (Frontend)
│── backend/          # NestJS (Backend)
│── docker-compose.yml # Docker configuration
│── .env.example      # Environment configuration
│── README.md         # Project documentation
```

## 🛠 **Installation & Setup**

### 1️⃣ **Clone the Repository**

```sh
git clone https://github.com/username/DeepSea.git
cd DeepSea
```

### 2️⃣ **Set Up Environment Variables**

Create a `.env` file in the project root and add the following configuration:

```sh
DATABASE_URL=postgres://user:password@postgres_db:5432/deepsea
PORT=3001
```

### 3️⃣ **Run the Application using Docker**

Ensure **Docker & Docker Compose** are installed, then execute:

```sh
docker-compose up --build -d
```

### 4️⃣ **Access the Application**

🌍 **Frontend:** `http://localhost:3000`\
️⚙ **Backend API:** `http://localhost:3001`

---

💡 **Contributions Welcome!** If you have suggestions or improvements, feel free to submit a **Pull Request** or open an **Issue**. 🚀

