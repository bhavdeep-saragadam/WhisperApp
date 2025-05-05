# Screen Share AI

A desktop application that allows users to quickly capture screenshots and get AI-powered analysis instantly using Google's Gemini Pro Vision API.

## 🚀 Development Plan

### Phase 1: Project Setup and Basic Structure (Week 1)
- [x] Initialize project with Electron.js
- [x] Set up development environment
- [x] Create basic project structure
- [ ] Configure build and packaging
- [ ] Set up testing framework

### Phase 2: Core Screenshot Functionality (Week 2)
- [ ] Implement screenshot capture utility
  - [ ] Hotkey registration
  - [ ] Screen overlay
  - [ ] Region selection
  - [ ] Image capture and processing
- [ ] Create basic UI for screenshot preview
- [ ] Implement system tray integration

### Phase 3: AI Integration (Week 3)
- [ ] Set up OpenAI API integration
- [ ] Implement image-to-text conversion
- [ ] Create AI response handling
- [ ] Add model selection functionality
- [ ] Implement error handling and retry logic

### Phase 4: UI/UX Development (Week 4)
- [ ] Design and implement popup window
- [ ] Create prompt input interface
- [ ] Add response display area
- [ ] Implement copy functionality
- [ ] Add loading states and animations

### Phase 5: Testing and Optimization (Week 5)
- [ ] Write unit tests
- [ ] Perform integration testing
- [ ] Optimize performance
- [ ] Implement error logging
- [ ] Add analytics (optional)

### Phase 6: Deployment and Documentation (Week 6)
- [ ] Create installers for different platforms
- [ ] Write user documentation
- [ ] Prepare release notes
- [ ] Set up auto-updates
- [ ] Create marketing materials

## 🛠️ Project Structure

```
screen-share-ai/
├── src/
│   ├── main/                 # Main process code
│   │   ├── main.js          # Main entry point
│   │   ├── screenshot.js    # Screenshot functionality
│   │   └── tray.js          # System tray management
│   ├── renderer/            # Renderer process code
│   │   ├── index.html       # Main window HTML
│   │   ├── styles/          # CSS styles
│   │   └── scripts/         # Frontend JavaScript
│   └── shared/              # Shared code between processes
│       ├── constants.js     # Shared constants
│       └── utils.js         # Utility functions
├── assets/                  # Static assets
├── tests/                   # Test files
├── docs/                    # Documentation
├── package.json            # Project configuration
└── README.md               # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- Google API key for Gemini Pro Vision

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/screen-share-ai.git
cd screen-share-ai
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory:
```
GOOGLE_API_KEY=your_google_api_key_here
```

4. Start the development server:
```bash
npm run dev
```

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details. # WhisperApp
# WhisperApp
