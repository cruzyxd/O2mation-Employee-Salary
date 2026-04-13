# O2mation Employee Salary System

A comprehensive HR and Payroll management system built with **React**, **Chakra UI**, and **PocketBase**.

## 🚀 Features

- **Employee Management**: Efficiently manage employee profiles and records.
- **Department Controls**: Organize employees into departments with hierarchical structures.
- **Payroll Processing**: Automated payroll calculation and generation (via PocketBase Event Hooks).
- **Transaction History**: Track all salary-related transactions.
- **Dynamic Stats**: Real-time dashboard statistics and visualization.
- **Multi-language Support**: Integrated Arabic and English translations using `i18next`.
- **Dark/Light Mode**: Full theme customization powered by Chakra UI.

## 🛠️ Tech Stack

- **Frontend**: React 19, Vite, TypeScript, Chakra UI
- **Backend/Database**: PocketBase
- **State Management**: Zustand, React Query (TanStack)
- **Internationalization**: i18next
- **Date Handling**: Luxon

## 📁 Project Structure

- `src/`: React application source code.
- `pb/`: PocketBase configuration and hooks.
  - `pb_hooks/`: Custom JavaScript event hooks for automated tasks (Payroll, Stats, Dumps).
- `documentation/`: Detailed developer guides and task breakdowns.
- `commands/`: Shell scripts for automating hook creation and verification.

## 🏁 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (latest LTS recommended)
- [PocketBase](https://pocketbase.io/) executable (included in `pb/`)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/cruzyxd/O2mation-Employee-Salary.git
   cd O2mation-Employee-Salary
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the project:
   - **Frontend**: `npm run dev`
   - **Backend**: Navigate to `pb/` and run `./pocketbase serve`

## 📜 Scripts

- `npm run dev`: Start Vite development server.
- `npm run build`: Build for production.
- `npm run typegen`: Generate TypeScript types from PocketBase schema.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](pb/LICENSE.md) file for details.
