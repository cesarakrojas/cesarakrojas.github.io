# Mini ERP System

A Next.js-based Enterprise Resource Planning (ERP) system designed to help small businesses manage their core operations. The system includes integrated modules for contact management, product catalog, sales processing, financial tracking, and inventory management with a configurable settings system and professional green theme.

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Open browser to http://localhost:3000
```

## ✨ Features

### 👥 Contact Management
- Manage customers and vendors with detailed contact information
- Advanced filtering and search capabilities
- Address management and notes system

### 📦 Product Catalog
- Support for both goods and services
- Vendor associations and pricing management
- SKU tracking and inventory configuration

### 💰 Sales Processing
- Create sales orders with multiple line items
- Automatic inventory reduction and financial recording
- Discount management and order tracking

### 📊 Financial Tracking
- Real-time transaction monitoring (income/expenses)
- Multi-currency support
- Automated integration with sales and purchases

### 📈 Inventory Management
- Real-time stock level tracking
- Weighted average cost calculation
- Purchase recording and stock adjustments
- Low stock alerts and reorder management

## 🏗️ Technology Stack

- **Frontend**: Next.js 14+ with App Router
- **Language**: TypeScript for type safety
- **Styling**: Tailwind CSS for responsive design
- **Data**: In-memory store (Firebase integration planned)

## 📁 Project Structure

```
src/
├── app/                    # Next.js App Router pages
│   ├── contacts/          # Contact management routes
│   ├── products/          # Product catalog routes  
│   ├── sales/             # Sales order routes
│   ├── balance/           # Financial transaction routes
│   └── inventory/         # Inventory management routes
├── components/            # Reusable UI components
├── lib/                   # Business logic and data handling
├── types/                 # TypeScript type definitions
└── hooks/                 # Custom React hooks
```

## 🔄 System Integration

The system features sophisticated cross-module integration:

- **Sales → Inventory**: Completed orders automatically reduce stock levels
- **Sales → Finance**: Revenue transactions are automatically recorded
- **Purchases → Inventory**: Stock additions with weighted average costing
- **Purchases → Finance**: Expense transactions are automatically recorded

## 🤝 Contributing

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/amazing-feature`
3. **Commit changes**: `git commit -m 'Add amazing feature'`
4. **Push to branch**: `git push origin feature/amazing-feature`
5. **Open a Pull Request**

### Development Guidelines

- Follow TypeScript best practices
- Use Tailwind CSS for styling
- Maintain modular component architecture
- Write descriptive commit messages
- Test cross-module integrations

## 🔮 Roadmap

- [ ] Firebase backend integration
- [ ] User authentication and authorization
- [ ] Advanced reporting and analytics
- [ ] Mobile-responsive improvements
- [ ] API documentation
- [ ] Unit and integration tests

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

If you encounter any issues or have questions:

1. Check the [Issues](../../issues) for existing solutions
2. Create a new issue with detailed description
3. Follow the issue template for faster resolution

---

**Built with ❤️ for small businesses looking to streamline their operations.**
