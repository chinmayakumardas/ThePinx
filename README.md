# ThePinx

An AI-powered bookmarking and automation platform that simplifies your digital life.

## Repository Structure

```
thepinx/
├── .github/
│   ├── workflows/
│   │   ├── ci.yml
│   │   └── deploy.yml
├── client/
│   ├── public/
│   │   ├── favicon.ico
│   │   ├── logo.svg
│   │   └── index.html
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   │   ├── common/
│   │   │   ├── layout/
│   │   │   └── features/
│   │   ├── hooks/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── store/
│   │   ├── utils/
│   │   ├── App.jsx
│   │   └── index.jsx
│   ├── .eslintrc.js
│   ├── package.json
│   └── vite.config.js
├── server/
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── services/
│   │   │   ├── ai/
│   │   │   ├── bookmark/
│   │   │   └── automation/
│   │   ├── utils/
│   │   └── app.js
│   ├── tests/
│   ├── .env.example
│   └── package.json
├── shared/
│   ├── constants/
│   ├── types/
│   └── utils/
├── scripts/
│   ├── setup.sh
│   └── seed-data.js
├── .gitignore
├── docker-compose.yml
├── Dockerfile
├── LICENSE
├── package.json
└── README.md
```

## Key Features

- **Smart Bookmarking**: AI-powered organization system
- **Quick Access**: Intuitive shortcuts for daily digital life
- **Automation Workflows**: Connect your bookmarks to automated processes
- **Cross-platform Sync**: Access your pins from any device
- **Tag Management**: Flexible organizing system
- **Search & Discovery**: Find what you need instantly
- **Browser Extensions**: Save content with a single click
- **Sharing & Collaboration**: Team features for shared collections

## Tech Stack

- **Frontend**: React, Redux, Tailwind CSS
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **AI Processing**: TensorFlow.js, OpenAI API
- **Authentication**: JWT, OAuth
- **Deployment**: Docker, GitHub Actions, AWS/Vercel

## Getting Started

1. Clone the repository
   ```
   git clone https://github.com/yourusername/thepinx.git
   cd thepinx
   ```

2. Install dependencies
   ```
   npm install
   cd client && npm install
   cd ../server && npm install
   ```

3. Set up environment variables
   ```
   cp server/.env.example server/.env
   # Edit the .env file with your credentials
   ```

4. Run the development environment
   ```
   npm run dev
   ```

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
