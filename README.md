# Sahyog Sync — Powering Collective Compassion

Sahyog Sync is a community-first digital ecosystem designed to bridge the critical gap between resource donors and the non-profit organizations (NGOs) that operate on the front lines of social impact. By providing a centralized, transparent platform, Sahyog Sync empowers local groups and volunteers to solve community challenges faster and more effectively.

---

## 🌟 Vision & Impact

In times of crisis or community need, the bottleneck is rarely a lack of willingness to help, but rather a lack of coordination. Sahyog Sync acts as the "operating system" for local compassion, ensuring that food, medicine, and manpower reach the right hands at the right time.

- **Transparency First**: Every kit shared and every hour volunteered is tracked, ensuring accountability.
- **Language for All**: We use human-centric language, stripping away technical jargon to make the platform accessible to everyone.
- **Premium Experience**: Helping others is a noble task; we believe the tools used for it should be beautiful, fast, and reliable.

---

## 🚀 Key Features

### 🏢 For NGOs (The Coordinators)
- **Centralized Dashboard**: A bird's-eye view of all operations, active needs, and volunteer status.
- **Inventory Management**: Track medicines, kits, and meals in real-time. Never run out of essentials.
- **Campaign Creation**: Launch specific aid campaigns with targeted goals and requirements.
- **Volunteer Coordination**: Review, approve, and assign tasks to local "Heroes."
- **Marketplace Alerts**: Get real-time notifications about available resources or urgent needs from other organizations.

### 🦸 For Volunteers (The Heroes)
- **Simple Onboarding**: Join the movement in seconds with a streamlined registration flow.
- **Task Discovery**: Find local projects that match your skills (Medical, Logistics, Support).
- **Impact Tracking**: See how your contributions directly help your community.

### 📊 For the Public
- **Live Impact Insights**: Real-time data on registered NGOs, active volunteers, and completed missions.
- **Verified Directory**: A trustworthy list of local organizations and their current activities.

---

## 🛠️ Technology Stack

Sahyog Sync is built with a modern, high-performance stack to ensure speed and reliability:

- **Frontend Core**: [React 19](https://react.dev/) + [Vite 8](https://vitejs.dev/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) for custom, responsive designs.
- **Animations**: [Framer Motion](https://www.framer.com/motion/) for fluid, premium transitions.
- **Mapping**: [Leaflet](https://leafletjs.com/) for visualizing community needs and NGO locations.
- **State Management**: Built-in React hooks and context for lightweight, efficient state.
- **API Communication**: [Axios](https://axios-http.com/) with centralized interceptors for secure requests.

---

## 💻 Getting Started

Follow these steps to get the Sahyog Sync frontend running on your local machine.

### Prerequisites
- [Node.js](https://nodejs.org/) (Version 18.0 or higher recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/SahyogSync-OS/sahyogsync-client.git
   cd sahyogsync-client
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   ```

4. **Access the application**
   Open [http://localhost:5173](http://localhost:5173) in your browser.

### Configuration
The application is pre-configured to point to our production backend at `https://sahyogsync.onrender.com`. 

For developers looking to run the full stack locally, the official backend repository can be found here: [sahyogsync-server](https://github.com/SahyogSync-OS/sahyogsync-server.git).

---

## 📂 Project Structure

```text
src/
├── components/     # Reusable UI components (Buttons, Modals, Navs)
├── pages/          # Feature-specific page modules
│   ├── admin/      # Platform moderation
│   ├── auth/       # Login and Registration
│   ├── ngo/        # NGO-specific dashboard and tools
│   ├── public/     # Landing page and impact insights
│   └── volunteer/  # Volunteer portal
├── services/       # API integration and utility functions
├── assets/         # Images, icons, and global styles
└── App.jsx         # Main application routing and providers
```

---

## 🤝 Contributing

We welcome contributions from the community! Whether it's fixing a bug, suggesting a feature, or improving documentation, your help makes Sahyog Sync better for everyone.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 🔗 Ecosystem
This client is powered by the **[Sahyog Sync Server](https://github.com/SahyogSync-OS/sahyogsync-server.git)**.

---

**Built with ❤️ by the Sahyog Sync Team.**
**Deployment: [sahyog-sync-frontend.vercel.app](https://sahyog-sync-frontend.vercel.app/)**

