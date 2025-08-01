<div align="center">


   <h1 align="center">AI Resume Analyzer</h1>
  
  <div>
    <img alt="React" src="https://img.shields.io/badge/React-19.1.0-4c84f3?style=for-the-badge&logo=react&logoColor=white">
    <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-5.8.3-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
    <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-4.1.4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white">
    <img alt="React Router" src="https://img.shields.io/badge/React_Router-7.5.3-CA4245?style=for-the-badge&logo=react-router&logoColor=white">
    <img alt="Puter.js" src="https://img.shields.io/badge/Puter.js-181758?style=for-the-badge&logoColor=white">
  </div>

 
  <p align="center">
    <strong>Smart feedback for your dream job!</strong><br>
    Upload your resume, get ATS scores, and receive personalized improvement tips powered by AI.
  </p>

  <div align="center">
    <p><strong>🚀 Ready to optimize your resume?</strong></p>
  </div>
</div>

## 📋 Table of Contents

- [✨ Introduction](#-introduction)
- [🚀 Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [📸 Screenshots](#-screenshots)
- [⚡ Quick Start](#-quick-start)
- [📖 Usage](#-usage)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

## ✨ Introduction

**AI Resume Analyzer** (Resumind) is a modern web application that helps job seekers optimize their resumes for Applicant Tracking Systems (ATS) and improve their chances of landing their dream job. Built with React, TypeScript, and powered by Puter.js for seamless authentication and AI analysis.

### Key Benefits:
- **ATS Optimization**: Get detailed scores and feedback on how well your resume performs in ATS systems
- **AI-Powered Analysis**: Receive personalized improvement suggestions based on specific job descriptions
- **Secure Storage**: Store and manage multiple resumes with cloud-based authentication
- **Real-time Feedback**: Instant analysis with comprehensive scoring across multiple categories

## 🚀 Features

### 🔐 Authentication & Storage
- **Seamless Login**: Browser-based authentication using Puter.js - no backend setup required
- **Secure File Storage**: Upload and store resumes securely in the cloud
- **Multi-Resume Management**: Organize and track multiple resume versions

### 📄 Resume Analysis
- **ATS Scoring**: Get a comprehensive ATS compatibility score (0-100)
- **Multi-Category Evaluation**: Detailed analysis across:
  - Overall Score
  - ATS Compatibility
  - Tone & Style
  - Content Quality
  - Structure & Format
  - Skills Assessment
- **Job-Specific Feedback**: Tailored recommendations based on job title and description
- **Visual Resume Preview**: View your resume as it appears to recruiters

### 🎯 Smart Recommendations
- **Personalized Tips**: Actionable improvement suggestions for each category
- **Good vs. Improve**: Clear distinction between strengths and areas for improvement
- **Detailed Explanations**: In-depth feedback with specific examples and guidance

### 🎨 Modern UI/UX
- **Responsive Design**: Works seamlessly across desktop, tablet, and mobile devices
- **Beautiful Interface**: Clean, professional design with smooth animations
- **Intuitive Navigation**: Easy-to-use interface for uploading and reviewing resumes
- **Real-time Processing**: Live status updates during resume analysis

## 🛠️ Tech Stack

### Frontend
- **React 19.1.0** - Modern UI library with hooks and functional components
- **TypeScript 5.8.3** - Type-safe JavaScript development
- **React Router 7.5.3** - Client-side routing with data loading
- **Tailwind CSS 4.1.4** - Utility-first CSS framework
- **Zustand 5.0.6** - Lightweight state management

### Backend & Services
- **Puter.js** - Serverless backend with auth, storage, and AI
- **PDF.js** - PDF processing and conversion
- **React Dropzone** - File upload handling

### Development Tools
- **Vite 6.3.3** - Fast build tool and dev server
- **CLSX** - Conditional CSS class names
- **Tailwind Merge** - Tailwind class merging utility

## 📸 Screenshots

### Landing Page
![Landing Page](public/bg-main.svg)
*Welcome to Resumind - Your AI-powered resume optimization companion*

### Authentication
![Authentication](public/home.svg)
*Secure, one-click authentication powered by Puter.js*

### Processing Animation
![Processing](public/images/resume-scan.gif)
*Real-time processing feedback during AI analysis*

## ⚡ Quick Start

### Prerequisites

Make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/) (v18 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [Git](https://git-scm.com/)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/adrianhajdin/ai-resume-analyzer.git
   cd ai-resume-analyzer
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
   Navigate to [http://localhost:5173](http://localhost:5173)

### Building for Production

```bash
npm run build
npm start
```

## 📖 Usage

### Getting Started

1. **Sign In**: Click "Log In" to authenticate using Puter.js
2. **Upload Resume**: Navigate to the upload page and select your PDF resume
3. **Add Job Details**: Enter the company name, job title, and job description
4. **Get Analysis**: Submit and wait for AI-powered analysis
5. **Review Feedback**: Explore detailed scores and improvement suggestions

### Understanding Your Results

#### ATS Score (0-100)
- **90-100**: Excellent - Your resume will likely pass ATS filters
- **70-89**: Good - Minor improvements recommended
- **50-69**: Fair - Several areas need attention
- **0-49**: Needs Work - Significant improvements required

#### Feedback Categories
- **Overall Score**: Comprehensive evaluation of your resume
- **ATS Compatibility**: How well your resume matches ATS requirements
- **Tone & Style**: Professional language and presentation
- **Content Quality**: Relevance and impact of your content
- **Structure**: Organization and formatting
- **Skills**: Technical and soft skills assessment

### Tips for Best Results

1. **Use PDF Format**: Ensure your resume is in PDF format for optimal processing
2. **Include Job Description**: Provide detailed job descriptions for more accurate feedback
3. **Review All Categories**: Pay attention to all feedback areas, not just the overall score
4. **Iterate and Improve**: Use the feedback to create multiple versions of your resume

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

### Development Setup

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Make your changes and test thoroughly
4. Commit your changes: `git commit -m 'Add amazing feature'`
5. Push to the branch: `git push origin feature/amazing-feature`
6. Open a Pull Request

### Guidelines

- Follow the existing code style and conventions
- Add tests for new features
- Update documentation as needed
- Ensure all tests pass before submitting

### Reporting Issues

- Use the GitHub issue tracker
- Provide detailed reproduction steps
- Include browser and OS information
- Attach relevant screenshots or logs

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Puter.js** for providing the serverless backend infrastructure
- **React Router** team for the excellent routing solution
- **Tailwind CSS** for the beautiful utility-first CSS framework
- **Open source community** for the amazing tools and libraries

## 📞 Support

- **GitHub Issues**: [Report bugs or request features](https://github.com/adrianhajdin/ai-resume-analyzer/issues)
- **Documentation**: Check the code comments and component structure for implementation details

---

<div align="center">
  <p>Made with ❤️ by the open source community</p>
</div>
