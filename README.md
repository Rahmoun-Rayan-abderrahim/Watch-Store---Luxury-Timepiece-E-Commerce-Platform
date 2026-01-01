<div align="center">

# 🕰️ **Watch Store - Luxury Timepiece E-Commerce Platform**

![React](https://img.shields.io/badge/React-19.2.0-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7.2.4-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.x-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

**An elegant and modern e-commerce platform specializing in luxury watches from premium brands worldwide.**

[Features](#-features) • [Installation](#-installation) • [Tech Stack](#-tech-stack) • [Project Structure](#-project-structure) • [Design System](#-design-system)

---

</div>

## 📋 **Table of Contents**

- [About The Project](#-about-the-project)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Installation](#-installation)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Pages & Routes](#-pages--routes)
- [Design System](#-design-system)
- [Brands & Collections](#-brands--collections)
- [Scripts](#-scripts)
- [Contributing](#-contributing)

---

## 🎯 **About The Project**

Watch Store is a premium e-commerce web application built with React and Vite, showcasing luxury timepieces from world-renowned watchmakers. The platform offers an immersive shopping experience with elegant design, smooth animations, and intuitive navigation through collections of high-end watches.

### **Key Highlights**
- ✨ **Modern UI/UX** - Sleek, luxury-focused design with smooth transitions
- 🛍️ **Shopping Cart** - Full cart functionality with quantity management
- 🔐 **User Authentication** - Login and Sign Up with localStorage persistence
- 🏷️ **Brand Collections** - Dedicated pages for 10 premium watch brands
- 🔍 **Filtering System** - Filter watches by gender (Men/Women)
- 📱 **Responsive Design** - Fully optimized for all device sizes

---

## ✨ **Features**

| Feature | Description |
|---------|-------------|
| 🏠 **Homepage** | Hero video banner with featured watch cards and brand showcase |
| 🕰️ **Watch Catalog** | Browse all watches with filtering options (Men/Women/All) |
| 🏪 **Brand Pages** | Individual pages for each luxury brand with their collections |
| 🛒 **Shopping Cart** | Add, remove, and manage items with quantity controls |
| 📝 **Contact Form** | Customer inquiry form with WhatsApp integration |
| 🔐 **Authentication** | User login and signup with form validation |
| 💬 **Testimonials** | Customer reviews and testimonials section |
| ⏰ **Coming Soon** | Upcoming watch releases with countdown timer |
| 🎨 **Elegant Design** | Luxury-themed color palette and typography |

---

## 🛠️ **Tech Stack**

### **Core Technologies**

| Category | Technology | Version |
|----------|-----------|---------|
| **Framework** | React | ^19.2.0 |
| **Build Tool** | Vite | ^7.2.4 |
| **Styling** | Tailwind CSS | 3.x |
| **Language** | JavaScript (ES6+) | - |

### **Key Dependencies**

```json
{
  "react": "^19.2.0",
  "react-dom": "^19.2.0",
  "vite": "^7.2.4"
}
```

### **Development Tools**

- **ESLint** - Code linting and quality checks
- **Vite HMR** - Hot Module Replacement for fast development
- **React Fast Refresh** - Instant UI updates during development

---

## 🚀 **Installation**

### **Prerequisites**

Make sure you have the following installed on your system:

- **Node.js** (v16.0 or higher recommended)
- **npm** or **yarn** package manager
- **Git** (for cloning the repository)

### **Step-by-Step Installation**

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd "Watch Store"
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   ```
   Navigate to http://localhost:5173 (or the port shown in terminal)
   ```

---

## 🎬 **Getting Started**

### **Development Mode**

```bash
npm run dev
```

Runs the app in development mode with hot-reload enabled. Open [http://localhost:5173](http://localhost:5173) to view it in the browser.

### **Production Build**

```bash
npm run build
```

Builds the app for production to the `dist` folder. The build is optimized and minified for best performance.

### **Preview Production Build**

```bash
npm run preview
```

Preview the production build locally before deploying.

### **Linting**

```bash
npm run lint
```

Run ESLint to check code quality and catch potential errors.

---

## 📁 **Project Structure**

```
Watch Store/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   ├── images/              # Watch images and brand logos
│   │   │   ├── Rolex.png
│   │   │   ├── Omega.png
│   │   │   ├── PatekPhilippe.png
│   │   │   └── ... (80+ watch images)
│   │   ├── bannervideo.mp4      # Homepage hero video
│   │   ├── Categoriesdata.js    # Watch collections data
│   │   ├── CategoriesHomedata.js # Brand data
│   │   ├── dummywdata.js        # Main watch catalog data
│   │   └── dummyStyles.js       # Centralized style definitions
│   ├── components/
│   │   ├── Navbar/              # Navigation component
│   │   ├── Footer/              # Footer component
│   │   ├── FashionPage/         # Homepage component
│   │   ├── WatchPage/           # Watch catalog page
│   │   ├── BrandPage/           # Individual brand pages
│   │   ├── CartPage/            # Shopping cart page
│   │   ├── ContactPage/         # Contact form page
│   │   ├── LoginPage/           # User login page
│   │   ├── SignUpPage/          # User registration page
│   │   ├── TestimonialPage/     # Testimonials section
│   │   └── ComingSoonWatchesPage/ # Coming soon watches
│   ├── App.jsx                  # Main application component
│   └── CartContext.jsx          # Shopping cart context/provider
├── index.html                   # HTML entry point
├── package.json                 # Dependencies and scripts
├── vite.config.js              # Vite configuration
└── README.md                    # Project documentation
```

---

## 🗺️ **Pages & Routes**

| Route | Component | Description |
|-------|-----------|-------------|
| `/` | FashionPage | Homepage with hero banner and brand showcase |
| `/watches` | WatchPage | Main watch catalog with filtering |
| `/brands/:brandSlug` | BrandPage | Individual brand collection pages |
| `/cart` | CartPage | Shopping cart with checkout form |
| `/contact` | ContactPage | Contact form with WhatsApp integration |
| `/login` | LoginPage | User authentication login |
| `/signup` | SignUpPage | New user registration |
| `/testimonials` | TestimonialPage | Customer reviews section |
| `/coming-soon` | ComingSoonWatchesPage | Upcoming releases with countdown |

### **Available Brand Routes**

- `/brands/rolex`
- `/brands/omega`
- `/brands/patek-philippe`
- `/brands/audemars-piguet`
- `/brands/cartier`
- `/brands/breitling`
- `/brands/iwc`
- `/brands/hublot`
- `/brands/tag-heuer`
- `/brands/jaeger-lecoultre`

---

## 🎨 **Design System**

### **Color Palette**

The application uses a sophisticated luxury watch store color scheme:

| Color | Usage | Hex/Class |
|-------|-------|-----------|
| **Gray-900/Black** | Primary backgrounds, text | `#111827` / `bg-gray-900` |
| **Gray-800** | Card backgrounds, borders | `#1F2937` / `bg-gray-800` |
| **Gray-600** | Secondary text, buttons | `#4B5563` / `bg-gray-600` |
| **Gray-300/400** | Borders, icons | `#D1D5DB` / `bg-gray-300` |
| **Amber-600** | Accent color, highlights | `#D97706` / `text-amber-600` |
| **Yellow-500** | Accent highlights | `#EAB308` / `text-yellow-500` |
| **White** | Primary text, card backgrounds | `#FFFFFF` / `bg-white` |

### **Typography**

| Font Family | Usage | Source |
|-------------|-------|--------|
| **Playfair Display** | Headings, elegant text | Google Fonts |
| **Poppins** | Body text, UI elements | Google Fonts |
| **Pacifico** | Brand name, decorative text | Google Fonts |
| **Dancing Script** | Special accents | Google Fonts |

### **Design Principles**

- **Luxury Aesthetic** - Clean, minimalist design with premium feel
- **Smooth Animations** - Subtle transitions and hover effects
- **Responsive Grid** - Flexible layouts adapting to all screen sizes
- **Card-based UI** - Consistent card design for products and content
- **Gradient Accents** - Subtle gradients for depth and elegance

### **Component Styles**

All styles are centralized in `src/assets/dummyStyles.js` with exported style objects:

- `bannerHomeStyles` - Homepage hero section
- `brandPageStyles` - Brand collection pages
- `cartPageStyles` - Shopping cart page
- `categoriesHomeStyles` - Brand showcase section
- `footerStyles` - Footer component
- `navbarStyles` - Navigation bar
- `loginPageStyles` - Login page
- `signUpStyles` - Sign up page

---

## 🏷️ **Brands & Collections**

### **Featured Luxury Brands**

The platform showcases watches from 10 prestigious watchmakers:

| # | Brand | Collections Available |
|---|-------|----------------------|
| 1 | **Rolex** | 8 models (Submariner, Daytona, GMT-Master, etc.) |
| 2 | **Omega** | 8 models (Seamaster, Speedmaster, Aqua Terra, etc.) |
| 3 | **Patek Philippe** | 8 models (Nautilus, Aquanaut, Calatrava, etc.) |
| 4 | **Audemars Piguet** | 8 models (Royal Oak, Code 11.59, etc.) |
| 5 | **Cartier** | 8 models (Santos, Tank, Ballon Bleu, etc.) |
| 6 | **Breitling** | 8 models (Navitimer, Superocean, Avenger, etc.) |
| 7 | **IWC** | 8 models (Big Pilot, Portugieser, Ingenieur, etc.) |
| 8 | **Hublot** | 8 models (Big Bang, Classic Fusion, etc.) |
| 9 | **Tag Heuer** | 8 models (Carrera, Monaco, Aquaracer, etc.) |
| 10 | **Jaeger-LeCoultre** | 8 models (Reverso, Master Control, Polaris, etc.) |

**Total Watch Catalog:** 80+ luxury timepieces

### **Watch Categories**

- **Men's Watches** - Professional, sport, and dress watches
- **Women's Watches** - Elegant, slim, and fashion-forward designs
- **All Watches** - Complete catalog view

---

## 📦 **Components Overview**

### **Core Components**

<details>
<summary><b>Navbar Component</b></summary>

- Sticky navigation with brand logo
- Desktop and mobile menu support
- Shopping cart badge with item count
- User authentication status display
- Active route highlighting

</details>

<details>
<summary><b>Footer Component</b></summary>

- Newsletter subscription form
- Quick links to collections
- Contact information
- Social media icons
- Watch pattern decorative overlay

</details>

<details>
<summary><b>Cart Context</b></summary>

- Global shopping cart state management
- Add/remove/update item functionality
- Price calculation and parsing
- LocalStorage persistence
- Quantity management

</details>

---

## 🔧 **Scripts**

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server with HMR |
| `npm run build` | Build for production (outputs to `dist/`) |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Run ESLint code analysis |

---

## 🌟 **Key Features in Detail**

### **Shopping Cart System**

- ✅ Add items to cart from watch pages
- ✅ Quantity increment/decrement controls
- ✅ Remove items functionality
- ✅ Real-time price calculation
- ✅ Persistent cart (localStorage)
- ✅ Cart badge showing item count

### **Authentication System**

- ✅ Login page with email/password
- ✅ Sign up page with validation
- ✅ Remember me functionality
- ✅ Toast notifications for feedback
- ✅ localStorage-based session management
- ✅ Protected routes support (ready for backend integration)

### **Brand Pages**

- ✅ Dynamic routing for each brand
- ✅ Brand-specific watch collections
- ✅ Watch cards with images and details
- ✅ Add to cart functionality
- ✅ Back navigation
- ✅ Responsive grid layout

### **Watch Filtering**

- ✅ Filter by gender (All/Men/Women)
- ✅ Icon-based filter buttons
- ✅ Real-time catalog updates
- ✅ Smooth transitions

---

## 🎯 **Future Enhancements**

Potential features for future development:

- [ ] Payment gateway integration
- [ ] User account dashboard
- [ ] Wishlist functionality
- [ ] Product search and sorting
- [ ] Order history tracking
- [ ] Backend API integration
- [ ] Email notifications
- [ ] Product reviews and ratings
- [ ] Advanced filtering (price, brand, etc.)
- [ ] Multi-language support

---

## 🤝 **Contributing**

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 **Notes**

- **Development Mode**: Uses Vite's fast HMR for instant updates
- **Styling**: Tailwind CSS utility classes with centralized style objects
- **State Management**: React Context API for cart state
- **Authentication**: Currently uses localStorage (ready for backend integration)
- **Images**: All watch images and brand logos stored in `src/assets/`
- **Data**: Watch and brand data stored in JavaScript modules

---

## 📄 **License**

This project is private and proprietary.

---

<div align="center">

**Built with ❤️ using React & Vite**

*Elegant Luxury Watch Shopping Experience*

[⬆ Back to Top](#-watch-store---luxury-timepiece-e-commerce-platform)

</div>
