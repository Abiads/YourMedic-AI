# YourMedic AI

An advanced AI-powered medical assistant platform that provides intelligent healthcare information and personalized medical assistance using cutting-edge AI technologies.

## Features

- AI-powered medical information retrieval
- Voice-based interaction
- Real-time medical data visualization
- Secure user authentication
- Responsive and modern UI
- Advanced security features
- Comprehensive logging and monitoring

## Tech Stack

### Frontend
- React.js
- Material-UI
- Chart.js
- Three.js for 3D visualizations
- Formik & Yup for form handling
- Speech recognition capabilities

### Backend
- Node.js with Express
- Firebase Admin SDK
- Winston for logging
- Security features (Helmet, Rate Limiting)
- CORS protection
- Request compression

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- Firebase project credentials

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Abiads/yourmedic-ai.git
cd yourmedic-ai
```

2. Install Frontend dependencies:
```bash
cd Frontend
npm install
```

3. Install Backend dependencies:
```bash
cd ../Backend
npm install
```

4. Set up environment variables:
Create a `.env` file in the Backend directory with the following variables:
```
NODE_ENV=development
PORT=3001
```

5. Add your Firebase credentials:
Place your Firebase service account key in `Backend/secret/secret.json`

### Running the Application

1. Start the Backend server:
```bash
cd Backend
npm run dev
```

2. Start the Frontend development server:
```bash
cd Frontend
npm start
```

The application will be available at `http://localhost:3000`

## Security Features

- Helmet.js for HTTP headers security
- Rate limiting to prevent abuse
- CORS protection
- Request compression
- Comprehensive logging system
- Input validation
- Secure authentication

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- React.js community
- Material-UI team
- Firebase team
- All contributors and maintainers
