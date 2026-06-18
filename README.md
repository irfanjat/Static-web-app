# Static Web App

A simple yet complete static web application with full CI/CD implementation. This project demonstrates best practices for building, containerizing, and deploying web applications using modern DevOps practices.

## 🎯 Project Overview

This repository contains a static web application built with HTML, CSS, and JavaScript, complete with Docker containerization and automated CI/CD pipelines. It serves as an excellent example of how to structure a web project with modern deployment practices.

## 📋 Tech Stack

- **Frontend**: 
  - HTML (39.5%)
  - CSS (31.2%)
  - JavaScript (8.2%)
- **DevOps**:
  - Docker (21.1%)
  - CI/CD Pipeline

## 📁 Project Structure

```
Static-web-app/
├── index.html           # Main HTML file
├── style.css            # Stylesheet
├── script.js            # JavaScript functionality
├── Dockerfile           # Docker container configuration
├── .github/
│   └── workflows/       # CI/CD workflows
└── README.md            # This file
```

## 🚀 Getting Started

### Prerequisites

- Node.js (optional, for local development)
- Docker (for containerization)
- Git

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/irfanjat/Static-web-app.git
   cd Static-web-app
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     python -m http.server 8000
     # or with Node.js
     npx http-server
     ```

3. **View at**
   - `http://localhost:8000` (or your configured port)

## 🐳 Docker

### Build Docker Image

```bash
docker build -t static-web-app:latest .
```

### Run Docker Container

```bash
docker run -p 80:80 static-web-app:latest
```

The app will be accessible at `http://localhost`

## 🔄 CI/CD Pipeline

This project includes automated workflows for:

- **Testing** - Validate code quality
- **Building** - Create Docker images
- **Deployment** - Deploy to production

Workflows are defined in `.github/workflows/`

## 📝 Features

- Clean and semantic HTML structure
- Responsive CSS styling
- Interactive JavaScript functionality
- Containerized deployment
- Automated CI/CD pipeline
- Docker support for easy distribution

## 🛠️ Development

### Making Changes

1. Edit HTML, CSS, or JavaScript files as needed
2. Test locally in your browser
3. Commit and push changes
4. CI/CD pipeline automatically triggers

### File Descriptions

- **index.html** - Main HTML markup
- **style.css** - Styling and layout
- **script.js** - Interactive functionality
- **Dockerfile** - Container configuration for deployment

## 📦 Deployment

The application is containerized using Docker for easy deployment across different environments. The included CI/CD pipeline automates the build and deployment process.

## 📄 License

This project is open source. Feel free to fork and modify as needed.

## 👤 Author

Created by [irfanjat](https://github.com/irfanjat)

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Open issues for bugs or feature requests
- Submit pull requests with improvements
- Suggest enhancements

## 📞 Support

For questions or issues, please open a GitHub issue in this repository.

---

**Last Updated**: 2026-06-18
