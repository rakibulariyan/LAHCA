LAET Admission Portal - Complete Solution
📋 Project Overview
LAET (Lower Assam Educational Trust) Admission Portal is a comprehensive web application for managing admission enquiries, featuring a responsive website with Google Sheets backend integration and automated email notifications.

🚀 Live Demo
Website: https://rakibulariyan.github.io/LAHCA/

Admission Form: Integrated Google Apps Script backend

✨ Key Features
🎨 Frontend Website
✅ Responsive Design - Works on all devices (mobile, tablet, desktop)

✅ Modern UI/UX - Clean, professional design with animations

✅ WhatsApp Chat Integration - Direct chat widget with multiple options

✅ Google Maps Integration - Location with directions functionality

✅ Festive Animations - New Year celebrations with confetti effects

✅ Scroll Progress Bar - Visual scroll indicator

✅ Smooth Animations - Fade-in effects and hover transitions

📊 Backend Integration
✅ Google Sheets Database - All enquiries stored in Google Sheets

✅ Automated Email System - Candidate & admin notifications

✅ Real-time Processing - Instant form submission handling

✅ Error Handling - Comprehensive error messages and validation

📧 Email System
✅ Candidate Confirmation - Professional HTML email with enquiry details

✅ Admin Notification - Urgent action-required emails

✅ Branded Templates - LAET branding with logo integration

✅ Dual Format - HTML and plain text email support

🛠️ Technology Stack
Frontend
HTML5 - Semantic markup

CSS3 - Custom properties, Flexbox, Grid, animations

JavaScript (ES6+) - Modern JavaScript with async/await

Font Awesome - Icon library

Google Fonts - Poppins & Montserrat fonts

Backend
Google Apps Script - Serverless backend

Google Sheets - Database

Gmail Service - Email delivery

Web App Deployment - REST API endpoint

📁 Project Structure
text
LAET-Admission-Portal/
├── index.html                    # Main website file
├── assets/
│   ├── uploads/
│   │   ├── LAET-logo.png        # Logo image
│   │   └── LAET-banner.png      # Banner image
│   └── css/                     # CSS files (if external)
├── google-apps-script/
│   └── LAET-Admission-Backend.js # Complete backend script
└── README.md                    # This documentation
🚀 Quick Setup Guide
1. Frontend Setup
Upload index.html to your hosting (GitHub Pages, Netlify, etc.)

Update contact information in the HTML file

Replace logo URL in the header section

Update WhatsApp phone number in JavaScript

2. Google Apps Script Setup
Step 1: Create Google Sheet
Create a new Google Sheet

Note the Sheet ID from URL: https://docs.google.com/spreadsheets/d/{SHEET_ID}/edit

Step 2: Create Google Apps Script
Go to script.google.com

Create new project

Copy the complete script from LAET-Admission-Backend.js

Update these variables:

javascript
const SHEET_ID = 'YOUR_GOOGLE_SHEET_ID_HERE';
const ADMIN_EMAIL = 'your-admin-email@example.com';
Step 3: Deploy as Web App
Click Deploy → New deployment

Settings:

Type: Web App

Execute as: Me

Who has access: Anyone

Copy the Web App URL

Step 4: Update Frontend
In index.html, update the Google Script URL:

javascript
const GOOGLE_SCRIPT_URL = "YOUR_WEB_APP_URL_HERE";
3. Email Configuration
Ensure your Google Account has Gmail sending permissions

Test email delivery by submitting a test form

Check spam folder if emails don't arrive

🔧 Configuration Options
Customization Points
Colors: Modify CSS variables in :root section

Contact Info: Update in contact section and emails

Courses: Modify in the Programs section

Email Templates: Customize HTML in Google Apps Script

Logo: Replace with your institution logo

WhatsApp Configuration
javascript
// Update in index.html JavaScript
const phone = '918638851516'; // Your WhatsApp number
Map Location
javascript
// Update coordinates in openDirections() function
const destLat = 26.338716076993997;
const destLng = 90.99848117413036;
📧 Email Templates
Candidate Email Features
Professional HTML design

Enquiry summary table

Contact information

Website link

Branded footer

Admin Email Features
Urgent notification design

Action required checklist

Direct links to email/call

Google Sheet access button

🐛 Troubleshooting
Common Issues & Solutions
1. Form Submission Fails
Check: Google Script URL is correct

Check: Web App deployment is active

Check: No CORS errors in browser console

2. Emails Not Sending
Check: Google Script has Gmail permissions

Check: Email quotas not exceeded

Check: Email addresses are valid

3. Google Sheet Not Updating
Check: Sheet ID is correct

Check: Sheet name matches (Admission Enquiries)

Check: Sheet has write permissions

4. WhatsApp Not Working
Check: Phone number includes country code

Check: Number has WhatsApp Business installed

Check: URL format: https://wa.me/918638851516

🔒 Security Considerations
Google Sheets: Set appropriate sharing permissions

Email Data: Contains PII - handle securely

Web App: Set to "Anyone" but data validation implemented

Form Validation: Client-side validation prevents spam

📈 Analytics & Monitoring
Built-in Tracking
Google Sheets Log: All submissions with timestamps

Email Logs: Sent emails tracked in Apps Script

Error Logging: Console errors captured

Recommended Additions
Google Analytics: Add tracking code

Submission Counter: Track total enquiries

Conversion Tracking: Monitor application completions

🎨 Design Customization
CSS Variables
css
:root {
    --primary-purple: #4C1D95;
    --primary-green: #059669;
    --whatsapp-green: #25D366;
    /* Customize these colors */
}
Logo Integration
Add logo to header: Replace emoji with <img> tag

Email logos: Update URLs in Google Apps Script

Favicon: Add to HTML head section

🤝 Contributing
Fork the repository

Create feature branch

Commit changes

Push to branch

Create Pull Request

📄 License
This project is developed for Lower Assam Educational Trust. For reuse or modification, please contact the institution.

📞 Support
For technical support:

Email: lahcabarpeta@gmail.com

Phone: +91 86388 12323 / +91 70024 64388

Address: Mayabini Path, Bylane 1, Near Uttar Barpeta Masjid, Uttar Barpeta, Barpeta, Assam 781301

🏆 Credits
Developed by: LAET IT Team
Backend: Google Apps Script
Design: Custom responsive design
Icons: Font Awesome
Fonts: Google Fonts

📊 Implementation Checklist
Google Sheet created and ID noted

Google Apps Script deployed

Web App URL copied

Frontend updated with script URL

Contact information verified

WhatsApp number updated

Logo uploaded and URLs updated

Test form submission

Test email delivery

Test WhatsApp functionality

Mobile responsiveness verified

Cross-browser testing completed

Last Updated: January 2026
Version: 2.0
Status: Production Ready ✅
