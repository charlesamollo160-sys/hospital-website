# Hospital Website - City General Hospital

A modern, responsive healthcare website for City General Hospital that provides patients with information about services, doctors, locations, and secure access to their patient portal.

## 🏥 Features

- **Home Page**: Welcome section with key highlights and call-to-action buttons
- **Find a Doctor**: Directory of healthcare professionals with search and filtering capabilities
- **Services**: Comprehensive list of medical services offered by the hospital
- **Locations**: Information about hospital locations and facilities
- **Patient Portal**: Secure login area for patients to:
  - View medical records and history
  - Manage appointments
  - Access lab results
  - View and pay bills online
- **Responsive Design**: Mobile-friendly interface that works on all devices
- **Modern UI**: Clean, professional design with intuitive navigation

## 📁 Project Structure

```
hospital-website/
├── index.html              # Home page
├── Find a Doctor.html      # Doctor directory page
├── Services.html           # Services information page
├── Locations.html          # Locations and facilities page
├── PatientPortal.html      # Patient portal with login
├── style.css               # Main stylesheet
└── README.md               # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Styling and responsive layout
- **JavaScript**: Interactive features and form handling
- **Font Awesome 6.0**: Icon library for visual elements
- **Responsive Design**: Mobile-first approach using media queries

## 🎨 Design Features

- **Color Scheme**: Professional blue and teal colors for healthcare branding
- **Typography**: Clean, readable fonts for accessibility
- **Navigation**: Sticky navbar with easy-to-access menu
- **Hero Sections**: Eye-catching header images on each page
- **Cards & Sections**: Organized content layout for better readability
- **Interactive Elements**: Hover effects and smooth transitions

## 💻 Pages Overview

### Index.html (Home)
Main landing page with:
- Hospital branding
- Key statistics and highlights
- Service overview
- Call-to-action buttons
- Footer with contact information

### Find a Doctor.html
Doctor directory featuring:
- Search functionality
- Doctor profiles with specialties
- Experience and qualifications
- Contact information

### Services.html
Service offerings including:
- Emergency Care
- Surgical Services
- Pediatrics
- Cardiology
- Radiology
- And more

### Locations.html
Hospital locations with:
- Multiple campus information
- Directions and contact details
- Hours of operation
- Parking information

### PatientPortal.html
Secure patient area with:
- Login authentication
- Patient records access
- Appointment management
- Lab results viewing
- Online billing system

## 🚀 Getting Started

1. **Clone the Repository**
   ```bash
   git clone https://github.com/charlesamollo160-sys/hospital-website.git
   ```

2. **Navigate to the Directory**
   ```bash
   cd hospital-website
   ```

3. **Open in Browser**
   - Open `index.html` in your web browser
   - Or use a local server:
     ```bash
     python -m http.server 8000
     # Then visit http://localhost:8000
     ```

## 📱 Responsive Breakpoints

- **Desktop**: Full layout (1024px and above)
- **Tablet**: Adjusted layout (768px - 1023px)
- **Mobile**: Single column layout (below 768px)

## 🔐 Security Notes

The current Patient Portal includes basic authentication UI. For production use, implement:
- Server-side authentication
- HTTPS encryption
- Secure password handling
- HIPAA compliance measures
- Database integration for patient data

## 📋 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎯 Future Enhancements

- Patient registration system
- Real-time appointment booking
- Online consultation features
- Automated appointment reminders
- Multi-language support
- Accessibility improvements (WCAG 2.1 AA)
- Backend API integration
- Database connectivity

## 📧 Contact Information

**City General Hospital**
- Phone: (XXX) XXX-XXXX
- Email: info@citygeneralhospital.com
- Website: www.citygeneralhospital.com

## 📄 License

This project is private and proprietary to City General Hospital.

## 👨‍💻 Developer Notes

- All styling is contained in `style.css`
- JavaScript functionality is embedded in each HTML file
- Font Awesome icons are loaded via CDN
- Ensure all images are optimized before deployment

---

**Last Updated**: May 14, 2026
**Version**: 1.0.0
