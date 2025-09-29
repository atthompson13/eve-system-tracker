# EVE System Tracker

A web application to track which systems a character has visited in EVE Online using the ESI API.

## Features

- 🗺️ Interactive map showing visited systems
- 📊 Statistics on exploration progress
- 🔐 Secure EVE Online SSO authentication
- 💾 Persistent tracking across sessions
- 📱 Responsive design for desktop and mobile

## Tech Stack

- **Frontend**: React with TypeScript
- **Backend**: Node.js with Express
- **Database**: PostgreSQL
- **Authentication**: EVE Online OAuth2 via ESI
- **Mapping**: Custom visualization with D3.js

## Getting Started

### Prerequisites

- Node.js 18+
- PostgreSQL 14+
- EVE Online Developer Application credentials

### Installation

1. Clone the repository:
```bash
git clone https://github.com/atthompson13/eve-system-tracker.git
cd eve-system-tracker