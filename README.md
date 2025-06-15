# Mental Health DB

<div align="center">
  
  ![License](https://img.shields.io/github/license/dev-gustavo-henrique/mental-health-db?color=blue)
  ![GitHub stars](https://img.shields.io/github/stars/dev-gustavo-henrique/mental-health-db?style=social)
  ![GitHub forks](https://img.shields.io/github/forks/dev-gustavo-henrique/mental-health-db?style=social)
  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
  ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
  
</div>

## 📋 About

Mental Health DB is a comprehensive web platform dedicated to providing information about mental health topics and services. The project's primary focus is on **accessibility**, ensuring that mental health resources are available to everyone, including those with visual or hearing impairments.

🌐 [Live Website](https://dev-gustavo-henrique.github.io/mental-health-db/)

## 🎯 Features

- Information on various mental health conditions:
  - Depression
  - OCD (Obsessive-Compulsive Disorder)
  - Anxiety
  - Bipolar Disorder
  - Burnout Syndrome
- Self-diagnosis awareness
- Emergency contact information
- Multilingual support

## 🔍 Accessibility Methods

The project implements various accessibility features to ensure inclusivity:

### 👁️ Visual Impairment Accessibility
- [x] Text-to-Speech (TTS) functionality
- [x] Dark Mode
- [x] High contrast options
- [x] Legible fonts
- [x] Semantic and accessible HTML

### 👂 Hearing Impairment Accessibility
- [x] VLibras Plugin (Brazilian Sign Language)
- [x] Videos with captions
- [x] Semantic and accessible HTML

### 🌍 Additional Accessibility Features
- [x] Language switching (Portuguese, English, Spanish)

## 🚀 Getting Started

### Prerequisites
- [Docker](https://www.docker.com/get-started) and [Docker Compose](https://docs.docker.com/compose/install/) (optional)
- Any modern web browser

### Installation

#### Method 1: Direct Download
1. Clone the repository:
   ```bash
   git clone https://github.com/dev-gustavo-henrique/mental-health-db.git
   ```
2. Open `index.html` in your web browser

#### Method 2: Using Docker
1. Clone the repository:
   ```bash
   git clone https://github.com/dev-gustavo-henrique/mental-health-db.git
   ```
2. Navigate to the project directory:
   ```bash
   cd mental-health-db
   ```
3. Build and run the Docker container:
   ```bash
   docker-compose up -d
   ```
4. Access the website at `http://localhost:8080`

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Docker (for containerization)
- Nginx (as web server in Docker)

## 📊 Project Structure

```
mental-health-db/
├── assets/
│   ├── css/         # Stylesheets
│   └── image/       # Images and logos
├── src/
│   ├── data/        # Data files including TTS audio
│   ├── services/    # Service integrations
│   └── script.js    # Main JavaScript file
├── docs/            # Documentation
├── index.html       # Home page
├── depression.html  # Depression information page
├── toc.html         # OCD information page
├── ansiedade.html   # Anxiety information page
├── bipolaridade.html # Bipolar disorder information page
├── burnout.html     # Burnout syndrome information page
├── Dockerfile       # Docker configuration
├── docker-compose.yml # Docker Compose configuration
└── README.md        # Project documentation
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgements

- Mental health professionals for guidance on content
- Accessibility experts for input on inclusive design
- Open source community for tools and libraries