# VideoBot Project

## Overview
VidBot is a full-stack application that combines AI-powered video generation with a modern web interface. The project consists of a React frontend and a Flask backend, working together to create and manage video content.

## Technologies Used

### Frontend
- React 19
- Vite (Build Tool)
- TailwindCSS (Styling)
- Framer Motion (Animations)
- React Router (Routing)
- shadcn/ui (UI Components)
- Lucide React (Icons)

### Backend
- Flask (Web Framework)
- Flask-CORS (Cross-Origin Resource Sharing)
- OpenAI API (AI Integration)
- MongoDB (Database)
- Cloudinary (Media Storage)
- Manim (Animation Engine)
- Docker (Containerization)

## Installation

### Prerequisites
- Node.js (v18+)
- Python (3.9+)
- Docker (optional)

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd Frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd Backend
   ```
2. Create a virtual environment:
   ```bash
   python -m venv venv
   ```
3. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Running the Development Servers

#### Frontend
```bash
cd Frontend
npm run dev
```

#### Backend
```bash
cd Backend
python app.py
```

### Docker Deployment
1. Build the Docker image:
   ```bash
   docker build -t videobot .
   ```
2. Run the container:
   ```bash
   docker run -p 8080:8080 videobot
   ```

## API Documentation

### Base URL
`http://localhost:8080/api`

### Endpoints
- `POST /generate`: Generate a new video
- `GET /videos`: List all generated videos
- `GET /videos/{id}`: Get details of a specific video

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with ❤️ by Team Decepticons  
![Team Logo](Frontend/public/decepticons.jpg){:width="150px"}