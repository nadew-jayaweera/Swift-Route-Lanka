# Technologies Used in Swift Route Lanka

This document provides a comprehensive overview of all technologies, libraries, tools, and services used in the Swift Route Lanka project.

---

## 📋 Table of Contents
- [Programming Languages](#programming-languages)
- [Frontend Technologies](#frontend-technologies)
- [Third-Party Libraries](#third-party-libraries)
- [Third-Party Services & APIs](#third-party-services--apis)
- [Hosting & Infrastructure](#hosting--infrastructure)
- [Development Tools](#development-tools)
- [Related Repositories](#related-repositories)

---

## 💻 Programming Languages

### HTML5
- **Version**: HTML5
- **Purpose**: Markup structure for all web pages
- **Features Used**:
  - Semantic HTML elements
  - Meta tags for SEO and viewport configuration
  - Embedded scripts and styles

### CSS3
- **Version**: CSS3
- **Purpose**: Styling and layout design
- **Features Used**:
  - Flexbox for responsive layouts
  - CSS Grid for complex layouts
  - Media queries for responsive design
  - CSS transitions and animations
  - Custom properties (CSS variables)
  - Backdrop filters for glassmorphism effects
  - Background images and gradients

### JavaScript (ES6+)
- **Version**: ES6+ (ECMAScript 2015+)
- **Purpose**: Client-side interactivity and business logic
- **Features Used**:
  - ES6 Modules (`import`/`export`)
  - Arrow functions
  - Template literals
  - DOM manipulation
  - Event listeners
  - Async/await patterns
  - Promise-based operations

---

## 🎨 Frontend Technologies

### Responsive Design
- **Mobile-first approach**: Media queries for various screen sizes
- **Breakpoints**: Optimized for mobile (≤768px) and desktop views
- **Flexible layouts**: Adapts to different viewport dimensions

### Custom Animations
- **CSS Animations**: Smooth transitions and hover effects
- **Interactive Elements**: Card hover effects, floating images, scroll animations
- **Navigation**: Toggle menu for mobile devices

---

## 📚 Third-Party Libraries

### Font Awesome
- **Version**: 6.4.2
- **Source**: CDN (`cdnjs.cloudflare.com`)
- **Purpose**: Icon library for UI elements
- **Icons Used**:
  - Social media icons (Facebook, Twitter, Instagram, YouTube, TikTok)
  - Navigation icons (bars/hamburger menu)
  - General UI icons
- **CDN Link**: `https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css`
- **Kit**: `https://kit.fontawesome.com/a076d05399.js`

### Google Fonts
- **Font**: Pacifico
- **Purpose**: Custom typography for branding and headers
- **Source**: Google Fonts API
- **Usage**: Main site title and section headings
- **CDN Link**: `https://fonts.googleapis.com/css2?family=Pacifico&display=swap`

---

## 🔌 Third-Party Services & APIs

### Firebase
Firebase is the primary backend service provider for the Swift Route Lanka platform.

#### Firebase Authentication
- **Version**: 11.10.0
- **Purpose**: User authentication and session management
- **Source**: Firebase CDN (`gstatic.com`)
- **Authentication Methods Supported**:
  - Email/Password authentication
  - Google OAuth authentication
  - Phone number authentication
- **Features Used**:
  - User registration
  - User login/logout
  - Session persistence
  - User state management (`onAuthStateChanged`)
  - Display name handling
- **Modules**:
  - `firebase-app.js` - Core Firebase SDK
  - `firebase-auth.js` - Authentication module
- **CDN Links**:
  - `https://www.gstatic.com/firebasejs/11.10.0/firebase-app.js`
  - `https://www.gstatic.com/firebasejs/11.10.0/firebase-auth.js`

#### Firebase Configuration
- **Project ID**: swift-route-lanka
- **Auth Domain**: swift-route-lanka.firebaseapp.com
- **Storage Bucket**: swift-route-lanka.firebasestorage.app
- **Messaging Sender ID**: 211170470678
- **App ID**: 1:211170470678:web:3845b18505650417a7be37
- **Measurement ID**: G-ZXP44MTRZ9 (Google Analytics)

### Google Maps API
- **Purpose**: Location-based services and mapping features
- **Usage**: Integrated across subdomain projects for displaying tourist locations and navigation

### Icons8
- **Purpose**: Payment method icons
- **Source**: Icons8 CDN
- **Icons Used**:
  - Visa
  - MasterCard
  - PayPal
  - American Express
  - Apple Pay
- **Base URL**: `https://img.icons8.com/color/48/000000/`

---

## 🌐 Hosting & Infrastructure

### GitHub Pages
- **Purpose**: Static website hosting
- **Features**:
  - Free SSL/TLS certificates
  - Custom domain support
  - Automatic deployment from repository
  - CDN-backed for global performance

### GoDaddy DNS
- **Purpose**: Domain name management and DNS configuration
- **Primary Domain**: `swiftroutelanka.xyz`
- **Subdomains Configured**:
  - `places.swiftroutelanka.xyz`
  - `packages.swiftroutelanka.xyz`
  - `contact.swiftroutelanka.xyz`
  - `login.swiftroutelanka.xyz`
  - `register.swiftroutelanka.xyz`
- **DNS Records**: CNAME records pointing to GitHub Pages

### Custom Domain
- **Domain**: swiftroutelanka.xyz
- **SSL/TLS**: Enabled via GitHub Pages
- **Configuration File**: CNAME file in repository root

---

## 🛠️ Development Tools

### Version Control
#### Git
- **Purpose**: Distributed version control system
- **Usage**: Track changes, manage branches, collaborate with team members

#### GitHub
- **Purpose**: Remote repository hosting and collaboration platform
- **Features Used**:
  - Repository hosting
  - Pull requests and code reviews
  - Issue tracking
  - GitHub Pages deployment
  - Branch management

### Code Editor
- **Recommended**: Any modern code editor (VS Code, Sublime Text, Atom, etc.)
- **No specific IDE requirements**: Plain HTML/CSS/JavaScript project

### Local Development Server
- **Optional Tool**: `npx serve .`
- **Purpose**: Local testing and development
- **Benefits**: Better CORS handling and local preview

### Browser Developer Tools
- **Purpose**: Debugging, testing, and performance optimization
- **Features Used**:
  - Console for JavaScript debugging
  - Network tab for monitoring requests
  - Elements inspector for CSS/HTML debugging
  - Responsive design mode for testing

---

## 📦 Related Repositories

The Swift Route Lanka project follows a modular architecture with separate repositories for different features:

| Repository | Purpose | Technologies |
|------------|---------|--------------|
| [Swift-Route-Lanka](https://github.com/nadew-jayaweera/Swift-Route-Lanka) | Main landing page and navigation | HTML, CSS, JavaScript, Firebase |
| [places-to-go](https://github.com/nadew-jayaweera/places-to-go) | Tourist destinations and attractions | HTML, CSS, JavaScript |
| [Packages](https://github.com/nadew-jayaweera/Packages) | Tour and vehicle rental packages | HTML, CSS, JavaScript |
| [Contact](https://github.com/nadew-jayaweera/Contact) | Contact form and communication | HTML, CSS, JavaScript |
| [login](https://github.com/nadew-jayaweera/login) | Firebase-based login functionality | HTML, CSS, JavaScript, Firebase Auth |
| [Register](https://github.com/nadew-jayaweera/Register) | Firebase-based user registration | HTML, CSS, JavaScript, Firebase Auth |

---

## 📊 Technology Stack Summary

### Core Stack
- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Backend/Services**: Firebase (Authentication, Hosting)
- **Hosting**: GitHub Pages with custom domain
- **DNS**: GoDaddy

### External Dependencies
- **UI Libraries**: Font Awesome 6.4.2
- **Fonts**: Google Fonts (Pacifico)
- **Icons**: Icons8
- **APIs**: Google Maps API (in subdomain projects)

### Development Environment
- **Version Control**: Git + GitHub
- **Deployment**: Automated via GitHub Pages
- **Local Testing**: Any local web server (optional)

---

## 🔄 Integration Architecture

```
┌─────────────────────────────────────────┐
│     Swift Route Lanka Main Site         │
│         (GitHub Pages)                  │
│    swiftroutelanka.xyz                  │
└─────────────────┬───────────────────────┘
                  │
     ┌────────────┼────────────┐
     │            │            │
┌────▼───┐   ┌───▼────┐   ┌──▼─────┐
│Places  │   │Packages│   │Contact │
│Subdomain│   │Subdomain│   │Subdomain│
└────────┘   └────────┘   └────────┘
     │            │            │
     └────────────┼────────────┘
                  │
          ┌───────▼────────┐
          │  Firebase Auth  │
          │  (login/register)│
          └────────────────┘
```

---

## 🔐 Security Considerations

### Firebase Security
- API keys are intentionally exposed for client-side Firebase SDK (public-facing)
- Firebase security rules should be configured server-side
- Authentication tokens managed securely by Firebase SDK

### HTTPS/SSL
- All domains served over HTTPS via GitHub Pages
- Secure communication for authentication and data transfer

---

## 📝 Notes for Developers

### Adding New Dependencies
When adding new libraries or services:
1. Update this TECHNOLOGIES.md file
2. Document the version, purpose, and usage
3. Update README.md if it's a major technology change
4. Consider CDN vs. local hosting for performance

### Browser Compatibility
- Modern browsers (Chrome, Firefox, Safari, Edge)
- ES6+ support required
- Mobile browsers fully supported

### Performance Optimization
- CDN-hosted libraries for faster loading
- Lazy loading for images
- Minification recommended for production (CSS/JS)

---

## 📚 Additional Resources

- [Firebase Documentation](https://firebase.google.com/docs)
- [Font Awesome Documentation](https://fontawesome.com/docs)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Google Fonts Documentation](https://fonts.google.com/)

---

**Last Updated**: 2025-11-08  
**Maintained By**: Swift Route Lanka Development Team
