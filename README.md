# ThinkAI-Website - Batteries Included Business Starter Template : Strapi5 + Next15 + Postgres + SocketIO

**ThinkAI-Website** - A `modern`, `cloud-native` `ready-to-use` business website `starter template` with all the batteries included from SEO to Reusable Blocks. Built using `Strapi 5` at Backend and `Next.js 15` at Frontend.


## 🚀 Features

- **Modern Tech Stack**: Strapi 5 + Next.js 15 + TypeScript + Tailwind CSS
- **SEO Optimized**: Built-in SEO components and meta tags
- **Responsive Design**: Mobile-first approach with modern UI/UX
- **Content Management**: Strapi CMS with custom content types
- **Performance**: Optimized images, lazy loading, and code splitting
- **Security**: Built-in security features and best practices
- **Scalability**: Docker containerization and cloud-ready
- **Real-time**: WebSocket support for live features
- **Analytics**: Built-in analytics and tracking
- **Multi-language**: Internationalization support
- **Blog System**: Full-featured blog with categories and tags
- **Contact Forms**: Multiple contact form types
- **Job Board**: Built-in job posting and application system
- **Portfolio**: Project showcase and case studies
- **Services**: Service catalog with detailed descriptions
- **Industries**: Industry-specific landing pages
- **Brand Kit**: Downloadable brand assets
- **Free Resources**: Resource library and downloads
- **Appointments**: Booking system integration
- **Live Streaming**: Built-in live streaming capabilities
- **AI Integration**: AI-powered features and chatbots
- **Modern APIs**: Latest web APIs and features
- **Three.js**: 3D graphics and animations
- **Particles**: Interactive particle effects
- **Spline**: 3D design integration
- **Vino**: Wine industry specific features
- **Robot Demo**: Robotics and automation demos
- **React 19**: Latest React features and demos

## 🛠️ Tech Stack

### Backend
- **Strapi 5**: Headless CMS
- **Node.js**: Runtime environment
- **TypeScript**: Type safety
- **PostgreSQL**: Primary database
- **Redis**: Caching and sessions
- **Socket.IO**: Real-time communication
- **JWT**: Authentication
- **Multer**: File uploads
- **Nodemailer**: Email services
- **Discord.js**: Discord bot integration
- **Sentry**: Error tracking
- **Algolia**: Search functionality

### Frontend
- **Next.js 15**: React framework
- **React 19**: UI library
- **TypeScript**: Type safety
- **Tailwind CSS**: Styling
- **Framer Motion**: Animations
- **Three.js**: 3D graphics
- **Particles.js**: Particle effects
- **Spline**: 3D design
- **Socket.IO Client**: Real-time features
- **React Hook Form**: Form handling
- **Zod**: Schema validation
- **Lucide React**: Icons

### DevOps
- **Docker**: Containerization
- **Docker Compose**: Multi-container setup
- **Nginx**: Reverse proxy
- **PM2**: Process management
- **GitHub Actions**: CI/CD
- **Cloudflare**: CDN and DNS
- **AWS S3**: File storage
- **Let's Encrypt**: SSL certificates

## 📦 Installation

### Prerequisites
- Node.js 18+ 
- Docker & Docker Compose
- Git

### Quick Start

```bash
# Clone the repository
git clone --depth=1 https://github.com/ciprianvladgherga/thinkai-website.git
cd  thinkai-website

# Install dependencies
npm run install:all

# Start development servers
npm run dev
```

### Docker Setup

```bash
# Start all services
npm run docker:up

# View logs
npm run docker:logs

# Access services
- Frontend: https://thinkaisolution.ro
- Backend: https://api.thinkaisolution.ro
- Admin: https://api.thinkaisolution.ro/admin
- Database: postgres:5432
```

## 🔧 Configuration

### Environment Variables

Create `.env` files in both `client/` and `server/` directories:

```bash
# Server (.env)
DATABASE_HOST=postgres
DATABASE_PORT=5432
DATABASE_NAME=strapi-thinkai
DATABASE_USERNAME=strapi
DATABASE_PASSWORD=strapi123
JWT_SECRET=your-jwt-secret
ADMIN_JWT_SECRET=your-admin-jwt-secret
API_TOKEN_SALT=your-api-token-salt
APP_KEYS=your-app-keys
TRANSFER_TOKEN_SALT=your-transfer-token-salt

# Client (.env.local)
NEXT_PUBLIC_STRAPI_BASE_URL=https://api.thinkaisolution.ro
NEXT_PUBLIC_BASE_URL=https://thinkaisolution.ro
```

### Database Setup

```bash
# Access database shell
docker  exec  -it  thinkai-strapi  bash

# Create admin user
npm run strapi admin:create-user
```

## 📱 Usage

### Development

```bash
# Start development servers
npm run dev

# Build for production
npm run build

# Start production servers
npm run start
```

### Docker Commands

```bash
# Start services
npm run docker:up

# Stop services
npm run docker:down

# View logs
npm run docker:logs

# Restart services
npm run docker:restart

# Rebuild containers
npm run docker:rebuild

# Clean up
npm run docker:clean
```

## 🌐 Deployment

### Production Deployment

```bash
# Build the application
npm run build

# Start production servers
npm run start

# Or use Docker
npm run docker:up
```

### Environment Variables for Production

```bash
# Server
DATABASE_HOST=your-db-host
DATABASE_NAME=your-db-name
DATABASE_USERNAME=your-db-user
DATABASE_PASSWORD=your-db-password
JWT_SECRET=your-production-jwt-secret
ADMIN_JWT_SECRET=your-production-admin-jwt-secret
API_TOKEN_SALT=your-production-api-token-salt
APP_KEYS=your-production-app-keys
TRANSFER_TOKEN_SALT=your-production-transfer-token-salt

# Client
NEXT_PUBLIC_STRAPI_BASE_URL=https://your-api-domain.com
NEXT_PUBLIC_BASE_URL=https://your-domain.com
```

## 📊 Monitoring

### Health Checks

- Frontend: `https://thinkaisolution.ro/api/health`
- Backend: `https://api.thinkaisolution.ro/api/health`
- Database: `postgres:5432`

### Logs

```bash
# View all logs
npm run docker:logs

# View specific service logs
npm run docker:logs:server
npm run docker:logs:client
npm run docker:logs:db
```

## 🔒 Security

- JWT authentication
- Role-based access control
- CORS configuration
- Rate limiting
- Input validation
- SQL injection protection
- XSS protection
- CSRF protection

## 📈 Performance

- Image optimization
- Code splitting
- Lazy loading
- Caching strategies
- CDN integration
- Database optimization
- Redis caching

## 🧪 Testing

```bash
# Run tests
npm test

# Run tests with coverage
npm run test:coverage

# Run specific tests
npm run test:unit
npm run test:integration
npm run test:e2e
```

## 📚 Documentation

- [Strapi Documentation](https://docs.strapi.io/)
- [Next.js Documentation](https://nextjs.org/docs)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License.

## Demo : http://thinkaisolution.ro

## 🆘 Support

- **Email**: `admin@thinkai.com`
- **Documentation**: [GitHub Wiki](https://github.com/ciprianvladgherga/thinkai-website/wiki)
- **Issues**: [GitHub Issues](https://github.com/- **Documentation**: [GitHub Wiki](https://github.com/ciprianvladgherga/thinkai-website/wiki/thinkai-website/issues)

If you encounter issues, feel free to [ open an issue](https://github.com/- **Documentation**: [GitHub Wiki](https://github.com/ciprianvladgherga/thinkai-website/wiki/thinkai-website/issues/new/choose).

Designed, Developed and Maintained by `ThinkAI Technologies`
