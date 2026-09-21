# 🏪 FranchiseOS

### Multi-Branch Business Management System

FranchiseOS is a full-stack business management platform designed for organizations operating multiple branches or franchise outlets.

The system centralizes **branch operations, inventory, sales, employees, suppliers, stock transfers, and business reporting** into a single management platform.

---

## 🚀 Features

### 🏢 Branch Management
- Create and manage multiple branches
- Store branch location and manager information
- Track active branches
- Centralized branch directory

### 📦 Central Inventory Management
- Product/SKU management
- Product categories
- Unit pricing
- Central stock tracking
- Automatic stock deduction after sales
- Inventory validation

### 💰 Sales Management
- Record branch-level sales
- Select branch and product
- Automatic sales calculation
- Quantity-based transactions
- Real-time inventory deduction
- Sales transaction ledger

### 👥 Employee Management
- Employee registration
- Role assignment
- Branch allocation
- Salary tracking
- Active employee monitoring

### 🚚 Stock Transfer Management
- Transfer inventory between branches
- Source and destination branch tracking
- Transfer quantity management
- Transfer status tracking
- Automatic stock deduction

### 🤝 Supplier Management
- Supplier directory
- Supplier contact information
- Supplier location tracking
- Centralized supplier records

### 📊 Business Intelligence Dashboard
- Total branches
- Active employees
- Product SKUs
- Total revenue
- Units sold
- Branch revenue comparison
- Top-performing products

### 📈 Consolidated Reporting
- Branch-wise revenue
- Transaction count
- Units sold
- Category-wise performance
- Revenue analysis

---

## 🛠️ Technology Stack

| Technology | Purpose |
|------------|---------|
| Python | Backend programming |
| Flask | Web framework |
| SQLite | Relational database |
| Jinja2 | Server-side templating |
| HTML5 | Frontend structure |
| CSS3 | UI styling |
| JavaScript | Frontend interactions |

---

## 🏗️ System Architecture

```text
                    ┌──────────────────────┐
                    │     FranchiseOS      │
                    │    Web Dashboard     │
                    └──────────┬───────────┘
                               │
              ┌────────────────┼────────────────┐
              │                │                │
       ┌──────▼──────┐ ┌──────▼──────┐ ┌──────▼──────┐
       │   Branches  │ │  Inventory  │ │    Sales    │
       └─────────────┘ └─────────────┘ └─────────────┘
              │                │                │
       ┌──────▼──────┐ ┌──────▼──────┐ ┌──────▼──────┐
       │  Employees  │ │  Suppliers  │ │  Transfers  │
       └─────────────┘ └─────────────┘ └─────────────┘
                               │
                        ┌──────▼──────┐
                        │   SQLite    │
                        │   Database  │
                        └─────────────┘
                               │
                        ┌──────▼──────┐
                        │ Consolidated│
                        │   Reports   │
                        └─────────────┘
