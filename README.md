# Moto Medic Pro

**The Complete Operating System for Motorcycle Ownership**

Moto Medic Pro combines a smart garage management system with AI-powered diagnostics to help riders maintain, repair, and upgrade their motorcycles with confidence.

## Features

### Smart Garage Management
- **Bike Tracking & Inventory**: Track every motorcycle with detailed specifications
- **Valuation Engine**: Real-time bike value estimation based on market data
- **Service History**: Complete maintenance and repair records
- **Parts Management**: Track inventory and upgrade history

### AI Mechanic Assistant
- **Diagnostic Engine**: AI-powered problem diagnosis and analysis
- **Repair Guidance**: Step-by-step repair instructions and tutorials
- **Cost Estimation**: Real-time repair and parts cost predictions
- **Knowledge Base**: Searchable library of common issues and solutions

### Build & Upgrade Tracking
- **Project Management**: Track custom builds and modifications
- **Investment Dashboard**: See exactly what you've invested in your bikes
- **Upgrade History**: Complete record of all modifications and upgrades
- **Net Worth Calculator**: Accurate bike valuation including investments

## Technology Stack

### Frontend
- **React.js** - Modern UI framework
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS** - Responsive styling
- **Redux** - State management
- **Next.js** - Server-side rendering & optimization

### Backend
- **Node.js/Express.js** - REST API server
- **PostgreSQL** - Relational database
- **AI/ML Integration** - Diagnostic engine & predictions
- **AWS/GCP** - Cloud infrastructure

### Infrastructure
- **Docker** - Containerization
- **GitHub Actions** - CI/CD pipeline
- **Vercel/Netlify** - Frontend deployment
- **Heroku/Railway** - Backend deployment

## Project Structure

```
MotoMedicpro/
├── frontend/                 # React.js web application
│   ├── src/
│   │   ├── components/       # Reusable UI components
│   │   ├── pages/            # Page components
│   │   ├── services/         # API services
│   │   ├── store/            # Redux store
│   │   └── hooks/            # Custom React hooks
│   ├── public/               # Static assets
│   └── package.json
├── backend/                  # Node.js/Express API
│   ├── src/
│   │   ├── routes/           # API routes
│   │   ├── controllers/      # Route handlers
│   │   ├── models/           # Database models
│   │   ├── middleware/       # Express middleware
│   │   ├── services/         # Business logic
│   │   ├── utils/            # Utilities
│   │   ├── ai/               # AI/ML services
│   │   └── config/           # Configuration
│   ├── database/             # Database migrations
│   └── package.json
├── shared/                   # Shared types & utilities
│   ├── types/                # TypeScript types
│   └── constants/            # Shared constants
├── docs/                     # Documentation
├── .github/workflows/        # CI/CD workflows
├── docker-compose.yml        # Development environment
└── README.md
```

## Quick Start

### Prerequisites
- Node.js 16+
- PostgreSQL 12+
- npm or yarn

### Development Setup

```bash
# Clone the repository
git clone https://github.com/motomonster-bit/MotoMedicpro.git
cd MotoMedicpro

# Install dependencies
npm install

# Setup environment variables
cp .env.example .env.local

# Start development servers
npm run dev

# Run migrations
npm run migrate

# Seed sample data
npm run seed
```

### Docker Setup

```bash
# Build and run with Docker Compose
docker-compose up

# Access the application
# Frontend: http://localhost:3000
# Backend: http://localhost:5000
```

## Deployment

### Production Deployment

```bash
# Build for production
npm run build

# Deploy frontend
npm run deploy:frontend

# Deploy backend
npm run deploy:backend
```

See [DEPLOYMENT.md](./docs/DEPLOYMENT.md) for detailed instructions.

## API Documentation

The API is documented using OpenAPI/Swagger. Access it at:
- Development: `http://localhost:5000/api/docs`
- Production: `https://api.motomedicpro.com/docs`

## Features Roadmap

- [ ] Mobile app (iOS/Android)
- [ ] Real-time notifications
- [ ] Multiplayer garage (shared ownership)
- [ ] Integration with parts retailers
- [ ] Video tutorial library
- [ ] Community forums
- [ ] Advanced analytics dashboard

## Contributing

See [CONTRIBUTING.md](./docs/CONTRIBUTING.md) for guidelines.

## License

MIT License - See [LICENSE](./LICENSE)

## Support

For issues and questions, please use the [Issues](https://github.com/motomonster-bit/MotoMedicpro/issues) tab.

---

**Made by riders, for riders.** 🏍️
