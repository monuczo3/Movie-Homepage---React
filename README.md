<div align="center">
  <img width="947" height="524" alt="image" src="https://github.com/user-attachments/assets/8776e2f2-ebe3-49de-9c0b-c9875740266b" />

  
  Modern Movie Discovery Platform
  
  <p>A Netflix-inspired movie discovery platform built with React.js, and TailwindCSS</p>

  <div>
    <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React.js" />
    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="TailwindCSS" />
  </div>
</div>

- 💫 **Modern UI/UX**:
  - Netflix-style hover effects
  - Smooth transitions
  - Responsive design
  - Dynamic loading states
 
  - ### For Developers
- 🏗️ **Clean Architecture**: Well-organized project structure
- 🔄 **Reusable Components**: Modular and maintainable code
- 📱 **Responsive Design**: Mobile-first approach
- 🚀 **Performance Optimized**: Fast loading and smooth interactions

## 🛠️ Tech Stack

- **Frontend**: 
  - React.js with Vite
  - TailwindCSS for styling
  - React Router for navigation
- **Backend**: 
  - TMDB API for movie data
- **Development**:
  - ESLint for code quality
  - Prettier for code formatting
  - Vite for fast development

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- TMDB API key

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/your-username/moodflix.git
cd moodflix
```

2. **Install dependencies**
```bash
npm install
```

3. **Environment Setup**

Create a `.env.local` file in the root directory:
```env
VITE_TMDB_API_KEY=your_tmdb_api_key
VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
```

4. **Start the development server**
```bash
npm run dev
```

Visit `http://localhost:5173` to view the application.

## 📦 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── MovieCard/      # Movie card component
│   ├── Search/         # Search component
│   └── ...
├── pages/              # Page components
│   ├── Home/          
│   └── MovieDetail/    
├── styles/             # Global styles
├── utils/              # Utility functions

```

## 🔧 Configuration


### TMDB Setup

1. Create an account on [TMDB](https://www.themoviedb.org/)
2. Get your API key from the settings
3. Add the API key to your environment variables
