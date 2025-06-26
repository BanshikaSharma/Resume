# 🧙‍♂️ Resume Wizard AI-Powered SaaS Application

This is a React-based SaaS application that enables users to create, manage, and preview **AI-powered Resumes**. The application utilizes **Vite, Tailwind CSS, Strapi, Clerk Authentication, and Gemini API** for AI-powered text generation. 👩‍💻💻📃💼

## Table of Contents

- [Getting Started](#getting-started)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Screenshots](#screenshots)
- [Project Files Structure](#project-files-structure)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/HamzaZaidiX/Resume-Wizard-AI-SAAS-App.git
```

2. Install dependencies:
```bash
cd resume-builder-ai
npm install
```

3. Create a `.env.local` file in the root directory and add the following variables:
```
VITE_STRAPI_API_KEY=your_strapi_api_key
VITE_GEMINI_API_KEY=your_gemini_api_key
```

4. Start the development server:
```bash
npm run dev
or
npm run start
```

## Features

- User authentication using **Clerk**
- **Create, Edit, View, Delete and Download Resumes**
- Preview Resumes with **AI-powered text Generation**
- Save resumes to **Strapi backend**
- Populate **resume data from User's profile**

## Demo Project Link:

## Technologies Used

- **React**: A **JavaScript library for building user interfaces**
- **Vite**: A **fast build tool for modern web apps**
- **Tailwind CSS**: A **utility-first CSS framework**
- **Strapi**: A **headless CMS for managing content backend and APIs**
- **Clerk**: A **user authentication and management library**
- **Gemini API**: An **AI-powered text generation API**






## Project Files Structure

```
resume-builder-ai/
├── public/
│   ├── favicon.ico
│   └── index.html
├── src/
│   ├── components/
│   ├── dashboard/resume/[resumeid]/edit
|   ├── my-resume/[resumeid]/view
│   ├── service/GlobalApi
|   ├── home/index.jsx
│   ├── App.jsx
│   ├── index.jsx
│   └── main.jsx
├── .env.local
├── package.json
├── README.md
└── vite.config.js
```

## API Documentation

- Strapi API: [https://strapi.io/documentation/v4.x/api-reference/](https://strapi.io/documentation/v4.x/api-reference/)
- Clerk API: [https://clerk.dev/docs/api](https://clerk.dev/docs/api)
- Gemini API: [https://www.gemini.com/api](https://www.gemini.com/api)

## Acknowledgments

- [Strapi](https://strapi.io/) for providing a powerful headless CMS
- [Clerk](https://clerk.dev/) for seamless user authentication
- [Gemini](https://www.gemini.com/) for AI-powered text generation
- [Tailwind CSS](https://tailwindcss.com/) for utility-first CSS framework
- [Vite](https://vitejs.dev/) for fast build

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## Bye! 👋
  HOPE U LIKE THIS PROJECT PLEASE! 
