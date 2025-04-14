# FC Pay - Payment Gateway System

A modern payment gateway system built with microservices architecture, featuring real-time fraud detection and asynchronous communication.

## Components

- **Web Interface** ([fc-pay-web](fc-pay-web)) - Next.js frontend for payment management
- **Payment Gateway** ([fc-pay-gateway](fc-pay-gateway)) - Go backend for payment processing
- **Fraud Detection** ([fc-pay-antifraud](fc-pay-antifraud)) - NestJS service for real-time fraud analysis

## Architecture

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