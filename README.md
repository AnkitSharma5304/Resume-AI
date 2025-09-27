# ResumeAI

<div align="center">
  <br />
  <h3 align="center">AI-Powered Resume Analysis Platform</h3>
  <p align="center">
    A modern web application that uses AI to analyze resumes and provide detailed feedback for job applications.
  </p>

  <div>
    <img alt="React" src="https://img.shields.io/badge/React-4c84f3?style=for-the-badge&logo=react&logoColor=white">
    <img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6">
    <img alt="Tailwind CSS" src="https://img.shields.io/badge/-Tailwind-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white">
    <img alt="Vite" src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white">
    </div>
</div>

## 🚀 Features

- **AI-Powered Analysis**: Get detailed feedback on your resume using advanced AI models
- **ATS Compatibility**: Check how well your resume performs with Applicant Tracking Systems
- **Job-Specific Feedback**: Upload job descriptions to get tailored recommendations
- **Modern UI/UX**: Clean, responsive design with a beautiful bluish theme
- **File Management**: Secure upload and storage of resume files
- **Real-time Scoring**: Instant feedback with detailed scoring across multiple categories
- **Cross-Platform**: Works seamlessly across all devices and browsers

## 🛠️ Tech Stack

- **Frontend**: React 19, TypeScript, Tailwind CSS
- **Routing**: React Router v7
- **State Management**: Zustand
- **Build Tool**: Vite
- **Backend Services**: Puter.js (Serverless authentication, storage, and AI)
- **PDF Processing**: PDF.js
- **File Upload**: React Dropzone

## 📋 Prerequisites

Before running this project, make sure you have:

- Node.js (v18 or higher)
- npm or yarn package manager
- Git

## 🚀 Quick Start

1. **Clone the repository**
```bash
git clone <your-repo-url>
cd resume-ai
```

2. **Install dependencies**
```bash
npm install
```

3. **Start the development server**
```bash
npm run dev
```

4. **Open your browser**
   Navigate to `http://localhost:5173` to view the application.

## 📁 Project Structure

```
resume-ai/
├── app/
│   ├── components/          # Reusable UI components
│   ├── lib/                # Utility functions and stores
│   ├── routes/             # Application routes
│   └── app.css            # Global styles
├── constants/              # Application constants
├── types/                  # TypeScript type definitions
└── public/                 # Static assets
```

## 🎯 Key Components

- **FileUploader**: Handles resume file uploads with drag-and-drop functionality
- **ResumeCard**: Displays resume information and scores
- **ScoreGauge**: Visual representation of resume scores
- **ATS**: ATS compatibility analysis component
- **Accordion**: Collapsible feedback sections

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run typecheck` - Run TypeScript type checking

## 🎨 Customization

The application features a modern bluish theme that can be easily customized by modifying the CSS variables in `app/app.css`. The color scheme includes:

- Primary blues for buttons and accents
- Subtle blue backgrounds
- Professional gradients
- High contrast text for accessibility

## 📱 Responsive Design

The application is fully responsive and optimized for:
- Desktop computers
- Tablets
- Mobile devices
- Various screen sizes and orientations

## 🔒 Security & Privacy

- All file uploads are handled securely through Puter.js
- User authentication is managed client-side
- No sensitive data is stored on external servers
- Files are processed locally when possible

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with modern web technologies
- Inspired by the need for better resume optimization tools
- Thanks to the open-source community for the amazing tools and libraries

---

<div align="center">
  <p>Built with ❤️ using React, TypeScript, and modern web technologies</p>
</div>