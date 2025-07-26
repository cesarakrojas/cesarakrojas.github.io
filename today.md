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

### ⚙️ Configurable Settings System
- **Gear Icon Access**: Settings accessible from all module headers with animated gear icons
- **Payment Methods Management**: Full CRUD operations for sales payment methods
- **Extensible Architecture**: Ready for additional module-specific configurations
- **Professional UI**: Modal-based settings with sidebar navigation

### 🎨 Custom Professional Theme
- **Green Color Scheme**: Custom branded navigation (#4A9462, #376F49)
- **Consistent Design**: Professional appearance across all modules
- **Accessible**: Maintained focus states and hover interactions

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
- **Configurable Payment Methods**: Cash, Credit Card, Bank Transfer, PayPal, and custom options


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
│   ├── GearIcon.tsx       # Animated settings gear icon
│   ├── SettingsModal.tsx  # Main settings modal component
│   ├── PaymentMethodsManager.tsx # Payment methods configuration
│   └── ...               # Other UI components
├── lib/                   # Business logic and data handling
│   ├── settings.ts        # Settings management system
│   └── ...               # Other business logic modules
├── types/                 # TypeScript type definitions
│   ├── settings.ts        # Settings-related types
│   └── ...               # Other type definitions
└── hooks/                 # Custom React hooks
```

## 🔄 System Integration

The system features sophisticated cross-module integration:

- **Sales → Inventory**: Completed orders automatically reduce stock levels
- **Sales → Finance**: Revenue transactions are automatically recorded
- **Purchases → Inventory**: Stock additions with weighted average costing
- **Purchases → Finance**: Expense transactions are automatically recorded
- **Settings Integration**: Configurable payment methods flow through sales processing
- **Cross-Module Settings**: Unified settings system accessible from all modules

## ⚙️ Settings & Configuration

### Payment Methods Management
- **Default Options**: Cash, Credit Card, Bank Transfer, PayPal
- **Custom Methods**: Add, edit, and organize payment options
- **Categories**: Organize by type (Cash, Card, Bank Transfer, Digital, Other)
- **Status Control**: Enable/disable methods without deletion
- **Business Rules**: Protected default method with validation

### Accessing Settings
1. Click the gear icon (⚙️) in any module header
2. Navigate through the sidebar for different settings categories
3. Currently available: Payment Methods (Sales module)
4. Future: Tax settings, contact validation, inventory thresholds, and more

## 🤝 Contributing

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/amazing-feature`
3. **Commit changes**: `git commit -m 'Add amazing feature'`
4. **Push to branch**: `git push origin feature/amazing-feature`
5. **Open a Pull Request**

### Development Guidelines

- Follow TypeScript best practices
- Use Tailwind CSS for styling (custom green theme: #4A9462, #376F49)
- Maintain modular component architecture
- Write descriptive commit messages
- Test cross-module integrations
- Use the settings system for configurable features
- Follow established patterns when adding new module settings


## 🔮 Roadmap

### ✅ Recently Completed
- [x] **Configurable Settings System**: Gear icons and payment methods management
- [x] **Custom Green Theme**: Professional branding with custom colors
- [x] **Cross-Module Integration**: Automated inventory and financial updates

### 🎯 Next Phase
- [ ] Extended settings for all modules (tax, validation, thresholds)
- [ ] Advanced payment method integration in sales workflow

### 🚀 Future Plans
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
