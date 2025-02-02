# Purrsuit 🐱💼

Purrsuit is a full-stack web application designed to help users find, adopt, and learn about cats in shelters. The project showcases my skills in front-end and back-end development, API integration, and responsive design.

## 🚀 Features

- **Search & Filter**: Users can browse and filter adoptable cats by breed, age, location, and temperament.
- **Favorites List**: Save and manage a list of favorite cats.
- **User Authentication**: Secure login and registration system.
- **API Integration**: Fetches real-time data from pet adoption APIs.
- **Responsive UI**: Fully optimized for mobile and desktop viewing.
- **Admin Dashboard**: Allows shelters to manage their listings.

## 🛠️ Tech Stack

### Frontend:
- **React**: Component-based UI development.
- **Tailwind CSS**: Modern styling for a sleek, responsive interface.
- **React Router**: For smooth client-side navigation.

### Backend:
- **Django**: High-level Python web framework for building a scalable backend.
- **Django REST Framework (DRF)**: To create a robust and flexible API.
- **PostgreSQL**: SQL database for structured and relational data management.
- **JWT Authentication**: Secure user authentication and session handling.

### Tools & Services:
- **Postman**: API testing and documentation.
- **GitHub Actions**: CI/CD for automated deployment.
- **Heroku/Render**: Backend hosting.
- **Netlify/Vercel**: Frontend hosting.

## 📂 Project Structure

```
Purrsuit/
│── frontend/   # React app
│── backend/    # Django server & database models
│── docs/       # Documentation and API specs
│── README.md   # Project overview
```

## 🏗️ Installation & Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/vmr093/Purrsuit.git
   ```
2. **Navigate to the project directory:**
   ```sh
   cd Purrsuit
   ```
3. **Install dependencies:**
   ```sh
   cd frontend && npm install
   cd ../backend && pip install -r requirements.txt
   ```
4. **Set up environment variables:**
   - Create a `.env` file in the `backend` directory.
   - Add credentials for PostgreSQL, JWT secrets, and API keys.
5. **Run the development servers:**
   ```sh
   cd backend && python manage.py runserver
   ```
   ```sh
   cd frontend && npm run dev
   ```
6. **Open the app in your browser:**
   ```
   http://localhost:8000
   ```

## 🎯 Future Improvements

- Implement a chatbot for adoption guidance.
- Add payment integration for donations.
- Improve accessibility features.

## 🤝 Contributions

Contributions are welcome! Feel free to fork the repo and submit a pull request.

## 📬 Contact

📧 **Email**: ranjha.viola@gmail.com  
🔗 **LinkedIn**: [Viola Ranjha](https://www.linkedin.com/in/viola-ranjha-858844133/)
