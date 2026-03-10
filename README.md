# FinTrackPro
A full-stack personal finance management app where users can track income/expenses, manage budgets, and monitor investment portfolios in real time.

## Core Features
Auth & User Management

## JWT-based authentication + refresh tokens
OAuth (Google login)

## Expense & Income Tracker

CRUD transactions with categories, tags, dates
Recurring transaction support

## Budget Module

Set monthly budgets per category
Visual progress bars + over-budget alerts

## Investment Portfolio Tracker

Add stocks/crypto holdings manually
Live price updates via a free API (e.g. Alpha Vantage, CoinGecko)
Portfolio value chart over time

## Analytics Dashboard

Spending breakdown (pie/donut charts)
Net worth over time (line chart)
Monthly cash flow (bar chart)
Built with Recharts or Chart.js

## Notifications / Alerts

Email alerts when over budget (Nodemailer)


### Tech Stack Breakdown
| Layer | Tech |
|-------|-------|
| Frontend | React + Redux Toolkit + Tailwind CSS |
| Backend | Node.js + Express.js |
| Database | MongoDB + Mongoose |
| Auth | JWT + bcrypt |
| Charts | Recharts |
| External API | Alpha Vantage (stocks) / CoinGecko (crypto) |
| Deployment | Vercel (frontend) + Render (backend) + MongoDB Atlas |
