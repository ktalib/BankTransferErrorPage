# Bank Transfer Error Page

A modern, responsive error page template specifically designed for banking and financial applications. Built with Tailwind CSS, this template provides a professional way to display transaction errors while maintaining user trust and providing clear next steps.

![ Error Page Preview](/api/placeholder/800/400)

## 🌟 Features

- **Professional Design**: Clean and modern UI suited for financial applications
- **Responsive Layout**: Works seamlessly across mobile, tablet, and desktop devices
- **Receipt Display**: Structured display of transaction details in a receipt format
- **Error Handling**: Clear error messaging with detailed explanations
- **Brand Customizable**: Easily adaptable to different banking brands
- **Accessibility**: Built with WCAG guidelines in mind
- **Real-time Status**: Network status detection and dynamic updates

## 🛠 Technologies Used

- HTML5
- Tailwind CSS
- Font Awesome Icons
- JavaScript (Vanilla)

## 🚀 Quick Start

1. **Clone the repository**
```bash
git clone https://github.com/ktalib/BankTransferErrorPage.git
cd BankTransferErrorPage
```

2. **Include Required CDNs**
```html
<!-- Tailwind CSS -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/2.2.19/tailwind.min.js"></script>

<!-- Font Awesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
```

3. **Customize the Content**
```html
<!-- Update the bank branding -->
<div class="bg-[#1D8753] rounded-xl p-4 inline-block">
    <span class="text-2xl font-bold text-white">Your Bank Name</span>
</div>

<!-- Update transaction details -->
<div class="font-semibold text-gray-800">Customer Name</div>
```

## 📋 Features Breakdown

### Receipt Section
- Recipient details display
- Transaction amount breakdown
- Service charges
- Current balance display

### Error Messaging
- Clear error headlines
- Detailed explanation
- Suggested next steps
- Support contact information

### Interactive Elements
- Back button
- Retry transaction button
- Support link
- Network status detection

## 🎨 Customization

### Colors
The template uses Tailwind CSS classes for styling. Main colors can be customized in your Tailwind config:

```javascript
module.exports = {
  theme: {
    extend: {
      colors: {
        primary: '#1D8753',  
        error: '#EF4444',    // Error red
        // Add your custom colors
      }
    }
  }
}
```

### Content
Update the error messages and transaction details in the HTML:

```html
<h1 class="text-2xl font-bold text-gray-800 mb-2">Your Error Title</h1>
<p class="text-gray-600">Your error description</p>
```

## 📱 Responsive Design

The template is fully responsive with breakpoints:
- Mobile: < 640px
- Tablet: 640px - 1024px
- Desktop: > 1024px

## 🔒 Security Considerations

- No sensitive data exposure in error messages
- Secure error handling patterns
- Clear user guidance for next steps
- Network status handled securely

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## 👏 Acknowledgments

- Tailwind CSS team for the amazing framework
- Font Awesome for the icons

## 📞 Support

For support, email iorkuakator@gmail.com or open an issue in the repository.

---

Made with ❤️ by Daniel