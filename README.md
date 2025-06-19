# Aegis Spend

Aegis Spend is a self-hosted expense tracker that helps you take control of your finances. It's built on a powerful, flexible, and open-source tech stack to give you clear insights into your spending.

## The Core Stack
Aegis Spend leverages three robust open-source tools:

- **Docker**: For consistent, easy deployment and management of all components
- **NocoDB**: Acts as the flexible backend, turning your database into a smart spreadsheet for easy data entry
- **Grafana**: Provides powerful visualizations, turning your expense data into insightful dashboards

## Get Started
Aegis Spend is designed for anyone looking for a powerful, customizable, and self-hosted solution for financial tracking.

To get your Aegis Spend instance running:

### 1. Launch the services
Open your terminal, navigate to your project's root directory (where your `docker-compose.yml` file is located), and run:

```bash
docker compose up -d
```

This command will:
- Download the necessary Docker images
- Start three containers:
  - Database (PostgreSQL)
  - NocoDB backend
  - Grafana dashboard

### 2. Access the services
After the containers start:

| Service  | URL                          | Default Credentials |
|----------|------------------------------|---------------------|
| NocoDB   | [http://localhost:8080](http://localhost:8080) | `admin@example.com` / `password` |
| Grafana  | [http://localhost:3000](http://localhost:3000) | `admin` / `admin`   |

