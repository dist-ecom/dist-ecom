# Distributed E-Commerce System

A modern, distributed e-commerce platform built with microservices architecture and a Next.js frontend.

## Project Structure

The project is organized into the following components:

### Frontend (`/frontend`)

- Built with Next.js 15.3.0 and React 19
- TypeScript support
- TailwindCSS for styling
- Modern development tools including Turbopack

### Services (`/services`)

- Microservices architecture
- Individual services for different business domains:
  - User Service
  - Product Service
  - Order Service

## Getting Started

### Prerequisites
- Node.js (latest LTS version)
- Docker
- Git

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

### Services Setup
Each service can be run independently using Docker. Navigate to the respective service directory and follow its README for specific setup instructions.

## Development

- The frontend runs on `http://localhost:3000` in development mode
- Each service runs on its own port (check individual service READMEs for details)
- Hot reloading is enabled for both frontend and services

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the terms of the LICENSE file in the root directory.