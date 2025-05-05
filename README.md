# BlagoDiy

BlagoDiy is a crowdfunding platform that allows users to create and manage fundraising campaigns, as well as make donations through LiqPay payment system.

## Features

- Campaign Management
  - Create fundraising campaigns with name, description, and category
  - Track campaign progress (raised amount vs destination goal)
  - Support for campaign images and social media links
  - Campaign duration management

- Donation System
  - Secure payments via LiqPay integration
  - Support for both authenticated and anonymous donations
  - Custom donation messages
  - Real-time donation tracking

- User Management
  - User registration and authentication
  - Personal campaign management
  - Donation history
  - Achievement system

## Technical Stack

- Backend: ASP.NET Core Web API
- Database: Entity Framework Core
- Payment Integration: LiqPay (Sandbox mode)
- Data Models:
  - Campaigns
  - Donations
  - Users
  - Achievements

## API Endpoints

### Payment API

```http
POST /api/pay
