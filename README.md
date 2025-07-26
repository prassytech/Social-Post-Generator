# Social Media Post Generator

A modern, responsive web application that generates engaging social media posts using Google's Gemini AI. Create customized content for different platforms with various tones in seconds.

## 🚀 Features

- **AI-Powered Content Generation**: Leverages Google Gemini AI to create engaging social media posts
- **Multi-Platform Support**: Generate posts optimized for Twitter, LinkedIn, Instagram, and Facebook
- **Customizable Tone**: Choose from professional, witty, casual, inspirational, humorous, or formal tones
- **Responsive Design**: Beautiful, mobile-friendly interface built with Tailwind CSS
- **Copy to Clipboard**: Easy one-click copying of generated content
- **Error Handling**: Robust error handling with retry mechanisms
- **Loading States**: Smooth user experience with loading indicators

## 🎯 Live Demo

[View Live Demo](https://prassytech.github.io/Social-Post-Generator/) <!-- Update this URL when deployed -->

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Tailwind CSS
- **Fonts**: Google Fonts (Inter)
- **AI API**: Google Gemini AI
- **Deployment**: GitHub Pages

## 📁 Project Structure

```
Social-Post-Generator/
├── index.html          # Main application file
└── README.md          # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- Google Gemini AI API key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/prassytech/Social-Post-Generator.git
   cd Social-Post-Generator
   ```

2. **Set up API Key**
   - Get your Gemini AI API key from [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Replace the placeholder API key in `index.html` with your actual key

3. **Open the application**
   - Simply open `index.html` in your web browser
   - Or use a local server for better development experience:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

## 💡 Usage

1. **Enter Your Topic**: Describe what you want to post about
2. **Select Tone**: Choose the appropriate tone for your audience
3. **Choose Platform**: Select your target social media platform
4. **Generate**: Click "Generate Post" and wait for AI magic
5. **Copy & Share**: Use the copy button to quickly share your content

## 🎨 Customization

### Styling
The application uses Tailwind CSS for styling. You can customize:
- Colors by modifying the color classes
- Layout by adjusting spacing and sizing classes
- Animations by updating the CSS animations

### Adding New Platforms
To add support for new social media platforms:
1. Add the platform option to the select dropdown
2. Update the prompt generation logic if needed

### Adding New Tones
To add new tone options:
1. Add the tone to the tone select dropdown
2. The AI will automatically adapt to the new tone

## 🔧 Configuration

### API Settings
You can modify the API configuration in the `callGemini` function:
- **Model**: Currently uses `gemini-2.5-flash-preview-05-20`
- **Retry Logic**: 3 attempts with exponential backoff
- **Timeout**: Configurable delay between retries

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Google Gemini AI** for powering the content generation
- **Tailwind CSS** for the beautiful styling framework
- **Google Fonts** for the Inter font family

## 📞 Contact

**Parth Patel** - [@prassytech](https://github.com/prassytech)

Project Link: [https://github.com/prassytech/Social-Post-Generator](https://github.com/prassytech/Social-Post-Generator)

---

⭐ Star this repository if you found it helpful!


