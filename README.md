# 🌊 Starfish PBX

**Starfish PBX** is a modern, web-based PBX interface built with React and JavaScript. It provides real-time visibility and control over VoIP infrastructure using a secure WebSocket backend and a global state store.

## 🚀 Features

- 🔄 **Live Data Sync** – Real-time updates over secure WebSocket (WSS)
- 🧠 **Global State Management** – Zustand store ensures consistent state across components
- 🧩 **Modular UI** – Clean React component architecture
- 🖥️ **Remote Agent Interaction** – Commands routed to and from PBX-connected agents
- 🔐 **Ready for Auth** – Designed to support JWT-based authentication and role-based access control (RBAC)

## 🛠️ Tech Stack

- **Frontend:** React, JavaScript, Zustand
- **Backend:** Express.js, WebSocket (WSS)
- **Optional Add-ons:** Google OAuth, JWT, Docker

## 📦 Installation

### Prerequisites

- Node.js (v18+)
- Yarn or npm

### Clone & Setup

```bash
git clone https://github.com/yourname/starfish-pbx.git
cd starfish-pbx
npm install    # or yarn
