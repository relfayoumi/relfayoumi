# 🖥️ AI Screen Share

A modern web-based screen capture tool designed for AI integration and real-time screen analysis.

## 🚀 Features

- **Real-time Screen Capture**: Share your entire screen, specific window, or browser tab
- **Live Preview**: See exactly what's being captured in real-time
- **Screenshot Capability**: Capture high-quality snapshots for AI analysis
- **AI-Ready Output**: Screenshots are optimized for AI vision models and OCR
- **Privacy-First**: All processing happens locally in your browser
- **No Installation Required**: Works directly in modern web browsers

## 🎯 Use Cases

- **AI Screen Analysis**: Capture screens for analysis by AI vision models
- **Visual Debugging**: Share screen content with AI assistants for troubleshooting
- **Content Recognition**: Enable AI to understand what's displayed on your screen
- **OCR Applications**: Extract text from screenshots using AI
- **Accessibility**: Help AI understand visual content for better assistance

## 🔧 How to Use

1. **Open the Tool**: Open `screen-share.html` in a modern web browser (Chrome, Edge, or Firefox recommended)

2. **Start Sharing**: Click "Start Screen Share" and select what you want to capture:
   - Entire screen
   - Specific application window
   - Browser tab

3. **Capture Screenshots**: Click "📸 Capture Screenshot" to take a snapshot

4. **Download or Share**: Download the screenshot or share it with AI tools for analysis

5. **Stop Sharing**: Click "Stop Sharing" when done

## 🤖 AI Integration

The captured screenshots are ready for integration with various AI services:

- **Vision APIs**: Compatible with GPT-4 Vision, Google Cloud Vision, Azure Computer Vision
- **OCR Processing**: Extract text from screen captures
- **Object Detection**: Identify elements and UI components
- **Screen Understanding**: Enable AI to understand interface layouts and content

## 💻 Technical Details

- **Technology**: Vanilla JavaScript, HTML5, CSS3
- **API Used**: Screen Capture API (`getDisplayMedia`)
- **Image Format**: PNG (lossless, high quality)
- **Browser Support**: Chrome 72+, Edge 79+, Firefox 66+, Opera 60+

## 🔒 Privacy & Security

- **No Server Required**: Everything runs locally in your browser
- **No Data Upload**: Screenshots are not automatically sent anywhere
- **User Control**: You decide what to share and when
- **Secure**: Uses browser's native security features

## 🌐 Browser Compatibility

| Browser | Support | Notes |
|---------|---------|-------|
| Chrome  | ✅ Yes  | Recommended |
| Edge    | ✅ Yes  | Recommended |
| Firefox | ✅ Yes  | Full support |
| Safari  | ⚠️ Limited | Version 13+ with limitations |
| Opera   | ✅ Yes  | Full support |

## 📋 Requirements

- Modern web browser with Screen Capture API support
- HTTPS connection (or localhost for testing)
- User permission to access screen/window content

## 🚦 Getting Started

Simply open the `screen-share.html` file in your browser:

```bash
# Using Python's built-in server
python -m http.server 8000

# Or using Node.js
npx serve

# Then visit: http://localhost:8000/screen-share.html
```

## 🛠️ Customization

The tool can be easily customized:

- Modify capture settings (resolution, frame rate)
- Add custom AI integrations
- Implement real-time processing
- Add cloud storage options
- Integrate with specific AI services

## 📝 License

This project is part of the Rel Fayoumi portfolio and is open for use and modification.

---

**Note**: Screen sharing requires user permission and works only in secure contexts (HTTPS or localhost).
