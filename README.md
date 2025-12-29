# PawPortal 🐾

A comprehensive pet adoption platform that connects potential pet adopters with NGOs and animal shelters. PawPortal provides an intuitive interface for users to find their perfect furry companion while offering powerful management tools for NGOs to showcase and manage their animals.
**LINK**- https://paw-portal-f651d.web.app/

## 🌟 Features

### For Pet Adopters
- **Pet Search & Discovery**: Browse and search for pets by breed, age, location, and other criteria
- **Detailed Pet Profiles**: View comprehensive information about each pet including photos, descriptions, and health status
- **Adoption Guide**: Complete step-by-step guide for first-time pet adopters
- **Health & Nutrition Guide**: Educational resources about pet care and nutrition
- **Training Tips**: Expert advice on pet training and behavior

### For NGOs & Shelters
- **NGO Dashboard**: Centralized management interface for animal shelters and NGOs
- **Pet Management**: Add, edit, and manage pet listings with detailed information
- **NGO Portal**: Dedicated portal for organizational management and oversight

## 🚀 Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Styling**: Custom CSS with modern design patterns, Google Fonts (Poppins), Font Awesome icons
- **Hosting**: Firebase Hosting
- **Architecture**: Static web application with responsive design

## 📁 Project Structure

```
inhouse/
├── firebase.json              # Firebase hosting configuration
├── README.md                 # Project documentation
└── website/                  # Main website files
    ├── index.html           # Main landing page with pet search
    ├── add-dog.html         # NGO form to add new pets
    ├── adoption-guide.html  # Complete adoption guide for users
    ├── health-nutrition-guide.html  # Pet health and nutrition information
    ├── ngo-dashboard.html   # NGO management dashboard
    ├── ngo-portal.html      # NGO organizational portal
    └── training-tips.html   # Pet training resources
```

## 🛠️ Setup & Installation

### Prerequisites
- Node.js (for Firebase CLI)
- Firebase CLI installed globally
- A Firebase project set up

### Local Development

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd inhouse
   ```

2. **Install Firebase CLI** (if not already installed)
   ```bash
   npm install -g firebase-tools
   ```

3. **Login to Firebase**
   ```bash
   firebase login
   ```

4. **Initialize Firebase** (if not already done)
   ```bash
   firebase init hosting
   ```

5. **Serve locally**
   ```bash
   firebase serve
   ```
   The application will be available at `http://localhost:5000`

### Deployment

Deploy to Firebase Hosting:
```bash
firebase deploy
```

## 🎨 Design Features

- **Modern UI/UX**: Clean, intuitive interface with smooth animations
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Accessibility**: Semantic HTML and proper contrast ratios
- **Performance**: Optimized images and efficient CSS
- **Visual Hierarchy**: Clear typography and consistent spacing

## 🔧 Configuration

The Firebase hosting configuration is set in `firebase.json`:
- Public directory: `website`
- Default route redirects to `/user.html`
- Ignores Firebase config files and node_modules

## 🌐 Pages Overview

| Page | Purpose | Target User |
|------|---------|-------------|
| `index.html` | Main landing page with pet search functionality | General users |
| `add-dog.html` | Form to add new pets to the database | NGO staff |
| `adoption-guide.html` | Comprehensive adoption guide and tips | Potential adopters |
| `health-nutrition-guide.html` | Pet health and nutrition information | Pet owners/adopters |
| `ngo-dashboard.html` | Administrative dashboard for NGOs | NGO administrators |
| `ngo-portal.html` | NGO management portal | NGO staff |
| `training-tips.html` | Pet training resources and advice | Pet owners |

## 🚧 Development Status

This project is currently in development. Some features may be incomplete:
- Pet search functionality (frontend ready, backend integration needed)
- NGO dashboard features (UI complete, database integration required)
- User authentication system (to be implemented)
- Pet adoption form processing (placeholder functionality)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 Future Enhancements

- [ ] User authentication and profiles
- [ ] Real-time chat between adopters and NGOs
- [ ] Pet matching algorithm
- [ ] Mobile application
- [ ] Payment integration for adoption fees
- [ ] Email notifications system
- [ ] Advanced search filters
- [ ] Pet adoption tracking system
- [ ] NGO verification system
- [ ] Multi-language support

## 📞 Contact & Support

For questions, suggestions, or support, please reach out to the development team.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

**Made with ❤️ for our furry friends**
