# Regalia Banquet & Resort Website

A luxury hotel and banquet website built with modern web technologies, featuring elegant design and comprehensive functionality for bookings, gallery, and contact management.

## 🏨 About the Project

Regalia Banquet & Resort is a premium hospitality website for a luxury resort located in Gorakhpur, Uttar Pradesh. The website showcases elegant banquet halls, luxurious rooms, fine dining restaurant, and swimming pool facilities, designed to provide an exceptional user experience for potential guests and event organizers.

## ✨ Features

### Core Functionality
- **Responsive Design** - Fully responsive across all devices (desktop, tablet, mobile)
- **Interactive Booking System** - Real-time availability checking and reservation forms
- **Image Gallery** - High-quality photo galleries with lightbox functionality
- **Contact Forms** - Multiple contact forms with validation and email integration
- **Mobile-First Navigation** - Slide-in mobile menu with smooth animations
- **Video Background** - Engaging hero section with video background
- **Testimonials Carousel** - Customer reviews with smooth transitions

### Pages & Sections
- **Home Page** - Hero section, about preview, amenities showcase, booking form
- **About Page** - Detailed resort information, facilities, FAQ section
- **Rooms** - Deluxe and Standard room showcases with detailed information
- **Restaurant** - Dining experience showcase with food gallery
- **Gallery** - Comprehensive photo gallery of facilities and events
- **Contact** - Contact information, forms, and Google Maps integration

### Technical Features
- **Form Validation** - Client-side and server-side form validation
- **Email Integration** - Web3Forms integration for contact and booking forms
- **SEO Optimized** - Proper meta tags, structured data, and semantic HTML
- **Performance Optimized** - Minified CSS/JS, optimized images, lazy loading
- **Cross-Browser Compatible** - Works seamlessly across all modern browsers

## 🛠️ Technologies Used

### Frontend
- **HTML5** - Semantic markup and modern HTML features
- **CSS3** - Advanced styling with Flexbox, Grid, and animations
- **JavaScript (ES6+)** - Modern JavaScript for interactivity
- **Bootstrap 5** - Responsive framework for layout and components
- **jQuery** - DOM manipulation and AJAX functionality

### Libraries & Frameworks
- **Owl Carousel** - For testimonials and image carousels
- **Jarallax** - Parallax scrolling effects
- **Isotope** - Filtering and layout for gallery
- **Font Awesome** - Icon library for UI elements
- **Google Fonts** - Custom typography (Montserrat, Caveat)

### Form Handling
- **Web3Forms** - Third-party form handling service
- **PHPMailer Integration** - Email functionality (validate.js)
- **AJAX Form Submission** - Seamless form submissions without page reload

### Why PHPMailer?

PHPMailer is integrated into this project for several compelling reasons:

#### 🔧 **Reliability & Stability**
- **Mature Library**: PHPMailer is one of the most established email libraries for PHP, with over 20 years of development
- **Proven Track Record**: Used by millions of websites worldwide, ensuring reliability in production environments
- **Regular Updates**: Actively maintained with security patches and feature improvements

#### 🛡️ **Security Features**
- **SMTP Authentication**: Secure email sending through authenticated SMTP servers
- **Encryption Support**: Built-in support for TLS/SSL encryption
- **Input Sanitization**: Automatic protection against email injection attacks
- **Secure Headers**: Proper email headers to prevent spoofing and improve deliverability

#### 📧 **Advanced Email Capabilities**
- **HTML & Plain Text**: Support for both HTML formatted and plain text emails
- **File Attachments**: Easy attachment handling for documents and images
- **Multiple Recipients**: Support for CC, BCC, and multiple TO recipients
- **Custom Headers**: Ability to set custom email headers for better control

#### 🚀 **Ease of Implementation**
- **Simple API**: Clean, intuitive API that's easy to implement and maintain
- **Extensive Documentation**: Comprehensive documentation with examples
- **Error Handling**: Robust error handling and debugging capabilities
- **Configuration Flexibility**: Easy configuration for different email providers

#### 🌐 **Integration Benefits**
- **Web3Forms Compatibility**: Works seamlessly with Web3Forms for hybrid form handling
- **Server Independence**: Can work with various hosting providers and email services
- **Fallback Option**: Provides a reliable fallback when third-party services are unavailable
- **Custom Branding**: Full control over email templates and branding

## 📁 Project Structure

```
Regalia-Git/
├── css/
│   ├── bootstrap.min.css          # Bootstrap framework
│   ├── style.css                  # Main stylesheet
│   ├── vendors.min.css            # Third-party CSS libraries
│   └── bs-icon-font/              # Bootstrap icons
├── js/
│   ├── common_scripts.js          # Core JavaScript functionality
│   ├── common_functions.js        # Utility functions
│   ├── datepicker_inline.js       # Date picker functionality
│   ├── datepicker_search.js       # Search date picker
│   ├── isotope.min.js             # Gallery filtering
│   └── slider.js                  # Carousel functionality
├── phpmailer/
│   └── validate.js                # Form validation and AJAX handling
├── img/
│   ├── rooms/                     # Room images
│   ├── restaurant/                # Restaurant images
│   └── [various image files]     # Site images and assets
├── video/
│   ├── s.mp4                      # Hero video (MP4)
│   └── sunset.ogv                 # Hero video (OGV)
├── index.html                     # Homepage
├── about.html                     # About page
├── contacts.html                  # Contact page
├── restaurant.html                # Restaurant page
├── gallery.html                   # Gallery page
├── room-list-2.html              # Rooms listing
├── DeluxRoom.html                # Deluxe room details
├── StandardRoom.html             # Standard room details
└── README.md                     # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Web server (Apache/Nginx) or local development server
- Modern web browser
- Internet connection (for CDN resources)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/regalia-resort.git
   cd regalia-resort
   ```

2. **Set up local server**
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Open in browser**
   ```
   http://localhost:8000
   ```

### Configuration

#### Form Setup
1. **Web3Forms Configuration**
   - Update the `access_key` in form elements
   - Current key: `0157d954-4db6-4ba2-9795-47ef108007b7`

2. **Contact Information**
   - Update phone numbers in floating buttons
   - Modify email addresses in contact sections
   - Update address information

3. **Google Maps**
   - Update the Google Maps embed URL in `contacts.html`
   - Current location: Gorakhpur, Uttar Pradesh

## 📱 Responsive Design

The website is fully responsive with breakpoints:
- **Mobile**: 320px - 768px
- **Tablet**: 768px - 1024px
- **Desktop**: 1024px+

### Mobile Features
- Slide-in navigation menu
- Touch-friendly buttons and forms
- Optimized image loading
- Floating contact buttons (Phone & WhatsApp)

## 🎨 Customization

### Colors & Branding
- Primary color: `#ebd7b2` (Gold accent)
- Phone button: `#760f10` (Dark red)
- WhatsApp button: `#34af23` (Green)

### Fonts
- Primary: Montserrat (Google Fonts)
- Accent: Caveat (Google Fonts)

### Images
- Hero images: 1920x1080px recommended
- Room images: 800x600px recommended
- Gallery images: Various sizes supported

## 📧 Contact Forms

### Form Types
1. **Booking Form** (Homepage)
   - Name, date, phone, subject, message
   - Web3Forms integration

2. **Contact Form** (Contact page)
   - Name, lastname, email, phone, message
   - Human verification (3+1=?)

3. **Restaurant Reservation** (Restaurant page)
   - Name, date, phone, message
   - Simple validation

### Form Validation
- Client-side validation using JavaScript
- Server-side validation through Web3Forms
- Success/error message display
- Form reset after successful submission

## 🔧 Maintenance

### Regular Updates
- Update contact information as needed
- Refresh gallery images periodically
- Monitor form submissions
- Update testimonials and reviews

### Performance Optimization
- Compress images before upload
- Minify CSS/JS files for production
- Enable browser caching
- Use CDN for static assets

## 🌐 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📊 SEO Features

- Semantic HTML structure
- Meta descriptions and keywords
- Open Graph tags for social sharing
- Structured data markup
- XML sitemap ready
- Mobile-friendly design
- Fast loading times

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## 👥 Credits

### Development Team
- **Frontend Development**: Shine Infosolutions
- **Design**: Custom responsive design
- **Content**: Regalia Banquet & Resort

### Third-Party Resources
- **Bootstrap**: Responsive framework
- **Font Awesome**: Icon library
- **Google Fonts**: Typography
- **Web3Forms**: Form handling service
- **Owl Carousel**: Image carousels
- **Jarallax**: Parallax effects

## 📞 Support

For technical support or questions:
- **Email**: info@shineinfosolutions.in
- **Website**: [Shine Infosolutions](https://www.shineinfosolutions.in/)
- **Phone**: +91-8112889999

## 🏨 Business Contact

**Regalia Banquet & Resort**
- **Address**: Gorakhnath Rd, near Value Plus Showroom, Rajendra Nagar, Gorakhpur, Uttar Pradesh 273015
- **Restaurant**: +91-8112879999
- **Banquet**: +91-8112889999
- **Email**: info@regalia.com

---

*Built with ❤️ by [Shine Infosolutions](https://www.shineinfosolutions.in/)*