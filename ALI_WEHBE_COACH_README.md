# Coach Ali Wehbe Website

A professional, responsive website for Coach Ali Wehbe - Certified International Relationships and Leadership Coach.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Arabic RTL Support**: Fully optimized for Arabic text with right-to-left layout
- **Modern UI/UX**: Beautiful blue gradients, animations, and professional styling
- **Bilingual Support**: Complete Arabic/English language switching
- **Contact Form**: Interactive contact form with validation
- **Social Media Integration**: Ready-to-use social media links
- **SEO Optimized**: Proper meta tags and semantic HTML structure

## Coach Details

- **Name**: Ali Wehbe (علي وهبة)
- **Specialization**: Relationships and Leadership Coach
- **Email**: Ali.wehbe@example.com
- **Phone**: +962 77 123 4567
- **Location**: Amman, Jordan
- **Working Hours**: Sunday - Thursday: 9:00 AM - 7:00 PM

## Sections

1. **Header/Navigation**: Fixed navigation with language toggle and booking button
2. **Hero Section**: Professional introduction with coach image
3. **Statistics**: 200+ successful clients, 98% satisfaction, 5+ years experience
4. **About Section**: Professional bio and credentials
5. **Services Section**: Three main services
   - Personal Relationships Training
   - Executive Leadership Development
   - Team Building
6. **Testimonials**: Client reviews with 5-star ratings
7. **Contact Section**: Contact information and contact form
8. **Footer**: Social media links and copyright

## Design Customizations

### Color Scheme
- **Primary Colors**: Blue theme (`#3b82f6`, `#2563eb`, `#60a5fa`)
- **Background**: Light blue gradient (`#dbeafe` to `#e0e7ff`)
- **Icons**: Users/relationships focused icons

### Key Differences from Template
- Changed from pink to blue color scheme
- Updated icons to reflect relationships/leadership focus
- Modified statistics (200+ clients, 98% satisfaction, 5+ years)
- Customized services for relationships and leadership coaching
- Updated testimonials with relevant client feedback
- Changed working hours to 9 AM - 7 PM

## Technical Features

- **Font**: Cairo (Arabic-optimized Google Font) + Inter (English)
- **Icons**: Font Awesome 6.0
- **Framework**: Tailwind CSS
- **Animations**: CSS animations with smooth transitions
- **Form Validation**: JavaScript form validation
- **Language Switching**: Dynamic content translation
- **Smooth Scrolling**: Native CSS smooth scrolling
- **Mobile Responsive**: CSS Grid and Flexbox layout

## Customization Guide

### Updating Coach Information

Edit these sections in the HTML:

```html
<!-- Coach Name in Header -->
<h2 class="text-lg font-semibold text-blue-500">علي وهبة</h2>

<!-- Hero Title -->
<h1 class="text-4xl md:text-5xl font-bold text-gray-800 mb-6">
    مرحباً! أنا علي وهبة، مدرب علاقات وقيادة معتمد دولياً
</h1>

<!-- Contact Information -->
<p class="opacity-90">+962 77 123 4567</p>
<p class="opacity-90">Ali.wehbe@example.com</p>
```

### Adding Coach Photo

Replace the placeholder image URLs:

1. **Hero Section Photo**: 
   - Replace the Unsplash URL in the hero section with actual coach photo
   
2. **About Section Photo**:
   - Replace the Unsplash URL in the about section with coach photo

### Customizing Services

To modify services, update the service cards:

```html
<div class="bg-gradient-to-br from-blue-50 to-indigo-50 p-8 rounded-2xl shadow-lg hover:shadow-xl transition-shadow">
    <div class="bg-blue-500 w-16 h-16 rounded-full flex items-center justify-center mb-6">
        <i class="fas fa-heart text-white text-2xl"></i>
    </div>
    <h3 class="text-xl font-bold text-gray-800 mb-4">Service Title</h3>
    <p class="text-gray-600 leading-relaxed">Service description...</p>
</div>
```

### Language Translations

Both Arabic and English translations are included in the JavaScript `translations` object. To add more languages or modify translations, update the translations object.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Template Replication Process

This website was created using the Abeer coach template with these modifications:

1. **Color Scheme**: Changed from pink to blue theme
2. **Coach Details**: Updated all personal information
3. **Specialization**: Changed from stress/anxiety to relationships/leadership
4. **Statistics**: Updated numbers and metrics
5. **Services**: Customized for leadership and relationships coaching
6. **Testimonials**: Updated with relevant client feedback
7. **Images**: Used professional leadership-focused stock photos

## Setup Instructions

1. Save the HTML file as `ali-wehbe-coach-website.html`
2. Add coach photos to the same directory (optional)
3. Update contact information and social media links
4. Open the file in a web browser to view

## Contact Form Integration

The contact form currently shows a success message. To make it functional:

1. **EmailJS Integration**: Add EmailJS service for client-side email sending
2. **Backend Integration**: Connect to a server-side form handler
3. **Third-party Services**: Use services like Formspree or Netlify Forms

## Deployment Options

- **GitHub Pages**: Free hosting for static websites
- **Netlify**: Free hosting with form handling
- **Vercel**: Free hosting with excellent performance
- **Traditional Web Hosting**: Upload to any web hosting service

## File Structure

```
ali-wehbe-coach-website.html    # Main website file
ALI_WEHBE_COACH_README.md      # This documentation file
```

## Future Coaches Template

This template can be easily replicated for other coaches by:

1. Copying the HTML file
2. Updating coach personal information
3. Changing color scheme (CSS variables)
4. Modifying specialization and services
5. Updating statistics and testimonials
6. Replacing images with coach photos

---

**Created with ❤️ for Coach Ali Wehbe**
*Professional Relationships and Leadership Coach*