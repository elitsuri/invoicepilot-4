# InvoicePilot

> Invoicing SaaS with recurring billing and tax management

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
Next.js, TypeScript, PostgreSQL, Stripe, Prisma

## 🏗️ Architecture
Backend service with Next.js, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/invoicepilot
cd invoicepilot

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
