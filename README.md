FinPort - Modern Banking Application
Overview
FinPort is a full-stack banking application built with Next.js that provides users with a seamless digital banking experience, including account management, transactions, and payment transfers.

Key Features
🏦 Bank Account Management - Connect and manage multiple bank accounts

💸 Payment Transfers - Send money between accounts

📊 Transaction History - View and analyze spending patterns

🔐 Secure Authentication - Sign up/sign in with email/password

📱 Responsive Design - Works on desktop and mobile devices

Technology Stack
Frontend
Next.js 14 (App Router)

TypeScript

Tailwind CSS

Shadcn/ui Components

React Hook Form for forms

Zod for validation

Backend & APIs
Appwrite (Backend service)

Plaid API (Bank connections)

Dwolla API (Payments processing)

Getting Started
Prerequisites
Node.js v18+

Appwrite instance

Plaid & Dwolla developer accounts

Installation
Clone the repository:

bash
git clone https://github.com/ChinmayDaroliya/FinPort.git
cd FinPort
Install dependencies:

bash
npm install
Set up environment variables:

Copy .env.example to .env

Fill in your API keys:

NEXT_PUBLIC_APPWRITE_PROJECT_ID=your_appwrite_id
NEXT_PUBLIC_APPWRITE_URL=your_appwrite_url
NEXT_PUBLIC_PLAID_PUBLIC_KEY=your_plaid_key
PLAID_CLIENT_ID=your_plaid_client_id
PLAID_SECRET=your_plaid_secret
DWOLLA_KEY=your_dwolla_key
DWOLLA_SECRET=your_dwolla_secret
Run the development server:

bash
npm run dev
Open http://localhost:3000 in your browser.

Project Structure
FinPort/
├── app/                  # Next.js app router pages
│   ├── (auth)/           # Authentication pages
│   ├── (root)/           # Main application pages
│   └── api/              # API routes
├── components/           # Reusable components
├── lib/                  # Utility functions
├── public/               # Static assets
├── types/                # TypeScript types
└── styles/               # Global styles
Contributing
Contributions are welcome! Please follow these steps:

Fork the project

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

License
Distributed under the MIT License. See LICENSE for more information.

Contact
Chinmay Daroliya - @yourtwitter - chinmaydaroliya@gmail.com

Project Link: https://github.com/ChinmayDaroliya/FinPort

Acknowledgments
Appwrite for backend services

Plaid for banking API

Dwolla for payment processing

Shadcn/ui for UI components
