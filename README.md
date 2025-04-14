# FC Pay - Payment Gateway System

A study project implementing a simple payment gateway system with microservices architecture, focusing on learning modern development practices.

## Components

- **Web Interface** ([fc-pay-web](https://github.com/brunownk/fc-pay-web)) - Next.js frontend for payment management
- **Payment Gateway** ([fc-pay-gateway](https://github.com/brunownk/fc-pay-gateway)) - Go backend for payment processing
- **Fraud Detection** ([fc-pay-antifraud](https://github.com/brunownk/fc-pay-antifraud)) - NestJS service for basic fraud analysis

## Study Focus

This project is designed for learning purposes, focusing on:
- Microservices architecture
- Event-driven communication
- Modern web development with Next.js
- Backend development with Go
- Service development with NestJS
- Basic payment processing concepts

## Tech Stack

- **Frontend**: Next.js with TypeScript
- **Backend**: Go with PostgreSQL
- **Fraud Detection**: NestJS with Kafka integration
- **Communication**: Apache Kafka for async messaging
- **Database**: PostgreSQL for data persistence

## Getting Started

1. Clone the repository with submodules:
```bash
git clone --recursive git@github.com:brunownk/fc-pay.git
```

2. Follow individual component READMEs for setup instructions.

## License

MIT