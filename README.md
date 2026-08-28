# ⚡ VoltCharge
Testing GitHub YOLO achievement - July 2026.
> Modern, open-source electric vehicle charging station locator & management app.

![VoltCharge Banner](./assets/banner.png) <!-- Replace with actual image -->

---

## 🚗 What is VoltCharge?

VoltCharge is a sleek and scalable EV charging station locator platform that enables users to find, book, and pay for electric vehicle charging stations in real-time. It is built with modern technologies and emphasizes usability, performance, and scalability. Inspired by real-world platforms like Bolt.Earth and developed with open-source values in mind.

---

## 🌟 Features

- 🔍 Station Locator with Google Maps integration  
- 🧠 Smart Route Planning  
- 💳 Payment Gateway Integration  
- ⛽ Real-Time Station Availability  
- 📱 Mobile-First Responsive UI  
- 🧾 Usage & Billing History  

---

## 🧱 Tech Stack

- **Frontend**: React 18, Tailwind CSS, Leaflet.js / Google Maps API  
- **Backend**: Node.js (Express) or Django  
- **Database**: PostgreSQL 14  
- **Authentication**: JWT-based  
- **CI/CD**: GitHub Actions  
- **Containerization**: Docker + Docker Compose  

---

## 🛠️ Installation

```bash
# Clone the repository
git clone https://github.com/vinnybellack/VoltCharge-A-Modern-EV-.git
cd voltcharge

# Install frontend dependencies
cd src/frontend
npm install
npm run dev

# Install backend dependencies
cd ../backend
npm install
npm run dev
```

> Ensure Docker and Node.js are installed to run services locally.

---

## 🐞 Sample Issues

1. **[Bug]** Map not centering on user’s location  
2. **[Feature]** Add dark mode  
3. **[Feature]** Add charger filter by power (Fast, Slow, Ultra)  
4. **[Enhancement]** Improve mobile responsiveness on station detail page  

---

## 📋 Project Management

Track issues and progress through the GitHub Projects board with the following columns:

- **Backlog**  
  - Integrate Leaflet.js as the default map renderer  
  - Set up database schema for charging stations and user bookings  
  - Plan UI wireframes and mobile layout structure

- **To Do**  
  - Create user registration and login flows  
  - Implement map component to show nearby chargers  
  - Develop backend API for station availability and booking

- **In Progress**  
  - Build responsive homepage layout using Tailwind CSS  
  - Test authentication using JWT  
  - Set up Docker environment for backend/frontend containers

- **Review**  
  - Code review for CORS middleware fix  
  - UI review for map overlay and responsiveness on mobile

- **Done**  
  - Initialized GitHub repo with project structure and documentation  
  - Added CI workflow using GitHub Actions  
  - Drafted README and issue templates

> Contributions are welcome! Start with a good first issue.  

> Contributions are welcome! Start with a good first issue.

---

## 🧠 Topics, Skills & Tools Used

- 🔧 React, Tailwind CSS, Leaflet.js / Google Maps API
- 🧩 Node.js / Express or Django REST Framework
- 🗃️ PostgreSQL for structured data management
- 🔐 JWT-based Authentication system
- 🐳 Docker for consistent containerized development
- 🚀 GitHub Actions for CI/CD pipelines
- 🧪 Git & GitHub for version control and collaboration
- 📝 Agile project tracking with GitHub Issues & Projects

---

## 🚧 Blockers Faced & Resolved

- ❌ **Map API quota limits**: Resolved by switching to Leaflet.js with open-source tiles as a fallback
- ❌ **Docker networking issues between frontend & backend**: Fixed via updated Docker Compose configuration
- ❌ **Cross-origin (CORS) errors**: Solved by enabling CORS middleware in backend server
- ❌ **Mobile responsiveness bugs**: Fixed with Tailwind breakpoints and UI testing

---

## 🪪 License

This project is licensed under the MIT License – see the [LICENSE](./LICENSE) file for details.

---

## 🙌 Contributing

We welcome contributions! Please fork the repository, create a branch, and submit a pull request. For major changes, open an issue first to discuss.

---

## 📞 Contact

For questions or feedback, connect via [LinkedIn](https://www.linkedin.com/in/vinod-balakrishnan-46937240/) or open a GitHub issue.
