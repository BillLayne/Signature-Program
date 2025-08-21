# 📝 Bill Layne Insurance Signature App

A professional, mobile-first electronic signature application for insurance documents. Built as a Progressive Web App (PWA) that works offline and can be installed on any device.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![PWA](https://img.shields.io/badge/PWA-ready-brightgreen.svg)
![Mobile](https://img.shields.io/badge/mobile-optimized-orange.svg)

## 🚀 Live Demo

**[Try it Live on GitHub Pages →](https://yourusername.github.io/signature-app/)**

### Quick Links with Pre-filled Templates:
- [Auto Insurance Claim](https://yourusername.github.io/signature-app/?template=auto_claim&autoload=true)
- [Home Insurance Application](https://yourusername.github.io/signature-app/?template=home_insurance&autoload=true)
- [General Consent Form](https://yourusername.github.io/signature-app/?template=consent_form&autoload=true)

## ✨ Features

### Core Functionality
- ✅ **Draw signatures** with pen/touch support
- ✅ **Multiple box types**: Signatures, Initials, Dates, Text, Checkboxes, Radio buttons
- ✅ **PDF Support**: Load, sign, and save PDF documents
- ✅ **Audit Trail**: Automatic generation with confirmation IDs
- ✅ **Print Ready**: Combined PDF with audit trail

### Advanced Features
- 📱 **PWA Support**: Install as native app on any device
- 🔄 **Offline Mode**: Works without internet connection
- 📋 **Templates**: Pre-configured layouts for common forms
- 🔗 **URL Parameters**: Pre-fill forms via links
- 🎨 **Customizable**: Multiple pen colors and sizes
- 📊 **Professional Output**: Includes headers, footers, and branding

## 📱 Installation

### As a Web App
Simply visit the site and start using immediately. No installation required!

### As a PWA (Recommended)
1. Visit the app in Chrome/Edge/Safari
2. Click the install icon in the address bar
3. Or click "Add to Home Screen" on mobile
4. The app will work offline once installed

## 🎯 Quick Start

### Basic Usage
1. **Open** a PDF document
2. **Switch modes**:
   - 📝 **Pen Mode**: Draw anywhere
   - 📦 **Box Mode**: Add signature fields
   - ✍️ **Sign Mode**: Fill in boxes
3. **Sign** the document
4. **Download** or **Print** with audit trail

### URL Parameters

Pre-fill forms by adding parameters to the URL:

```
https://yoursite.github.io/signature-app/?name=John+Doe&policy=NC-123456&template=auto_claim
```

#### Available Parameters:
- `name` - Pre-fill signer name
- `policy` - Pre-fill policy number
- `template` - Load template (auto_claim, home_insurance, consent_form)
- `autoload` - Auto-open file picker

### Examples:
```bash
# Pre-fill customer information
?name=Jane+Smith&policy=HOME-789012

# Load with auto insurance template
?template=auto_claim&autoload=true

# Complete setup for returning customer
?name=Bob+Johnson&policy=AUTO-456789&template=auto_claim
```

## 🛠️ Box Types

| Type | Icon | Purpose | Interaction |
|------|------|---------|------------|
| Signature | ✍️ | Full signature | Draws name in cursive |
| Initials | ✏️ | Quick initials | Auto-generates from name |
| Date | 📅 | Current date | Auto-fills today's date |
| Text | 📝 | Custom text | Opens text input dialog |
| Checkbox | ☑️ | Yes/No options | Toggle check on/off |
| Radio | ⭕ | Multiple choice | Select one per group |

## 📋 Templates

### Built-in Templates:

1. **Auto Insurance Claim**
   - Policyholder signature
   - Date field
   - Initials box

2. **Home Insurance Application**
   - Applicant signature
   - Date field
   - Coverage checkboxes

3. **General Consent Form**
   - Signature field
   - Date field
   - Printed name text box

### Creating Custom Templates:
Edit the `formTemplates` object in the main HTML file to add your own.

## 🔐 Security & Compliance

- ✅ ESIGN Act compliant
- ✅ UETA compliant
- ✅ Unique confirmation IDs
- ✅ Tamper-evident audit trail
- ✅ Timestamp tracking
- ✅ No data leaves your device

## 💻 Technical Details

### Technology Stack
- **Frontend**: Pure HTML5, CSS3, JavaScript
- **PDF Processing**: PDF.js, pdf-lib
- **Hosting**: GitHub Pages compatible
- **PWA**: Service Worker, Web Manifest
- **No Backend Required**: 100% client-side

### Browser Support
- ✅ Chrome/Edge (Recommended)
- ✅ Safari/iOS
- ✅ Firefox
- ✅ Mobile browsers

### File Structure
```
signature-app/
├── improved-signature-app claude updated with print.html  # Main application
├── manifest.json                                          # PWA manifest
├── service-worker.js                                      # Offline support
├── README.md                                              # Documentation
├── icon-192.png                                          # App icon (create)
└── icon-512.png                                          # App icon (create)
```

## 🚀 Deployment

### GitHub Pages Setup
1. Fork this repository
2. Go to Settings → Pages
3. Select source: "Deploy from branch"
4. Choose branch: main, folder: root
5. Save and wait for deployment
6. Access at: `https://yourusername.github.io/repository-name/`

### Custom Domain
1. Add CNAME file with your domain
2. Configure DNS to point to GitHub Pages
3. Enable HTTPS in repository settings

## 📈 Future Enhancements

- [ ] Cloud storage integration (Google Drive, Dropbox)
- [ ] Multi-signer workflow
- [ ] Email notifications
- [ ] Form field auto-detection
- [ ] Signature verification
- [ ] Batch processing
- [ ] API for third-party integration

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

MIT License - feel free to use in your own projects!

## 🏢 About Bill Layne Insurance

Bill Layne Insurance Agency  
1283 N Bridge St, Elkin NC 28621  
Phone: (336) 835-1993  
Email: Save@BillLayneInsurance.com  
Website: www.BillLayneInsurance.com

---

**Note**: Remember to create `icon-192.png` and `icon-512.png` for the PWA icons. You can use any image editor or online tool to create these from your company logo.