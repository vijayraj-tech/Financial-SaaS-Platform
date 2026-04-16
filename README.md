#  Horizon – Financial SaaS Platform

## Introduction
Horizon is a financial SaaS platform built with Next.js that connects multiple bank accounts, displays transactions in real-time, allows users to transfer money, and manage finances in one place.

## Tech Stack
- Next.js  
- TypeScript  
- Appwrite  
- Plaid  
- Dwolla  
- React Hook Form  
- Zod  
- TailwindCSS  
- Chart.js  
- ShadCN  

## Features
-  Secure Authentication  
-  Connect multiple bank accounts (Plaid)  
-  Dashboard with total balance & analytics  
-  View all connected banks  
-  Transaction history with filters & pagination  
-  Real-time updates  
-  Funds transfer using Dwolla  
-  Fully responsive UI  

## Getting Started
## Install dependencies 
- npm install
## Setup environment variables
Create a .env.local file and add:

NEXT_PUBLIC_SITE_URL=

NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
NEXT_PUBLIC_APPWRITE_PROJECT=
APPWRITE_DATABASE_ID=
APPWRITE_USER_COLLECTION_ID=
APPWRITE_BANK_COLLECTION_ID=
APPWRITE_TRANSACTION_COLLECTION_ID=
APPWRITE_SECRET=

PLAID_CLIENT_ID=
PLAID_SECRET=
PLAID_ENV=sandbox
PLAID_PRODUCTS=
PLAID_COUNTRY_CODES=

DWOLLA_KEY=
DWOLLA_SECRET=
DWOLLA_BASE_URL=https://api-sandbox.dwolla.com
DWOLLA_ENV=sandbox

## Run the project
