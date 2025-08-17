1# Story-Teller

A React-based web application that leverages Google's Gemini AI to generate stories with illustrations, presented in a beautiful **book interface** with PDF export and text-to-speech capabilities. This project was created during the PanScience hackathon.

🌐 **Live Demo:** [https://story-teller-enhanced.vercel.app/](https://story-teller-enhanced.vercel.app/)

📚 **GitHub Repository:** [https://github.com/DreamerAkhilesh/Story-Teller-enhanced-.git](https://github.com/DreamerAkhilesh/Story-Teller-enhanced-.git)

## 🚀 Features

- **AI Story Generation**: Interactive story generation using Gemini AI
- **AI-Generated Illustrations**: 5 related animated images for each story
- **📚 Book-First Interface**: Beautiful book layout with two-page spreads
- **📄 PDF Export**: Download generated stories as professional book-style PDFs
- **🔊 Text-to-Speech**: Listen to stories being read aloud with adjustable speed
- **Modern React Components**: Built with React 19 and modern hooks
- **Enhanced UI/UX**: Beautiful gradients, animations, and responsive design
- **Fast Development**: Optimized with Vite

## 🆕 Enhanced Book Interface

### 📚 Interactive Book Experience
- **Book-Only Interface**: Stories automatically display in beautiful book layout
- **Enhanced Cover Page**: Stunning design with floating animations and decorative elements
- **Two-Page Spreads**: Images on left, text on right for perfect reading experience
- **Beautiful Cover Page**: Gradient design with story metadata and decorative elements
- **Smooth Navigation**: Previous/Next buttons with page indicators
- **Quick Page Access**: Jump to any page or cover instantly
- **Enhanced Animations**: Page flip effects, hover animations, and smooth transitions

### 🎨 Visual Enhancements
- **Gradient Backgrounds**: Beautiful blue-to-purple gradients throughout
- **Enhanced Typography**: Gradient text effects and improved readability
- **Smooth Animations**: Hover effects, page transitions, and loading states
- **Professional Layout**: Clean, modern design with proper spacing and shadows
- **Responsive Design**: Perfect experience on all devices and screen sizes

## 🛠️ Tech Stack

- [React 19](https://react.dev/) - Latest React with modern hooks
- [Vite](https://vitejs.dev/) - Next Generation Frontend Tooling
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Google Generative AI](https://ai.google.dev/) - Google's Gemini AI API
- [jsPDF](https://github.com/parallax/jsPDF) - PDF generation library
- [html2canvas](https://html2canvas.hertzen.com/) - HTML to canvas conversion
- [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API) - Native text-to-speech
- ESLint - For code linting and maintaining code quality

## 📦 Prerequisites

- Node.js (Latest LTS version recommended)
- npm or yarn package manager

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/DreamerAkhilesh/Story-Teller-enhanced-.git
   cd Story-Teller-enhanced-
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add your Gemini API key:
   ```
   VITE_GEMINI_API_KEY=your_api_key_here
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

The application will be available at `http://localhost:5173`

## 📖 How to Use

### 1. Generate a Story
1. Enter your story prompt in the enhanced text area
2. Click "✨ Generate Story & Images" button
3. Watch the beautiful loading animation
4. Your story automatically opens in book mode!

### 2. Experience the Book Interface
1. **Cover Page**: Beautiful gradient design with story metadata
2. **Navigate Pages**: Use Previous/Next buttons or page indicators
3. **Two-Page Spreads**: Images on left, story text on right
4. **Quick Access**: Jump to any page using the numbered buttons
5. **Smooth Animations**: Enjoy page flip effects and hover animations

### 📄 Enhanced PDF Export
- **Book-Style PDF**: Professional layout with cover page and two-page spreads
- **Custom Dimensions**: 800x600pt landscape format matching book UI display
- **High-Quality Images**: Maximum JPEG quality (1.0) with enhanced resolution
- **Professional Layout**: Two-page spreads with images on left, text on right
- **Enhanced Typography**: Larger fonts and better spacing for readability
- **Perfect for Digital**: Optimized for screen viewing and digital sharing

### 4. Listen to Your Story
1. Click "🔊 Read Aloud" to start text-to-speech
2. Adjust reading speed with the enhanced slider (0.5x to 2x)
3. Use "🔇 Stop Speaking" to pause or "⏹️ Stop" to end
4. Enjoy natural voice reading of your story

### 5. UI Features
- **Gradient Backgrounds**: Beautiful blue-to-purple theme
- **Enhanced Animations**: Smooth transitions and hover effects
- **Responsive Design**: Perfect on all devices
- **Professional Layout**: Clean, modern interface

## 📝 Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the application for production
- `npm run lint` - Run ESLint to check code quality
- `npm run preview` - Preview the production build locally

## 🏗️ Project Structure

```
Story-Teller-enhanced-/
├── public/            # Public assets
├── src/              # Source code
│   ├── assets/       # Static assets
│   ├── App.jsx       # Main application component
│   ├── App.css       # Application styles
│   ├── main.jsx      # Entry point
│   └── index.css     # Global styles
├── .env              # Environment variables
├── index.html        # HTML entry point
├── package.json      # Project dependencies and scripts
└── vite.config.js    # Vite configuration
```

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

## ✨ Acknowledgments

- Thanks to Google for providing the Gemini AI API
- PanScience hackathon organizers and participants

## 🔧 Development Notes

This project uses Vite with React for optimal development experience, featuring Hot Module Replacement (HMR) and ESLint integration. The official [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) plugin is used for Fast Refresh functionality.
