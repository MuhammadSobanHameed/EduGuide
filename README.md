# 🎓 EduGuide AI – Educational Content Generator 

EduGuide AI is a comprehensive **AI-powered educational platform** designed to assist **teachers** in creating high-quality academic content and help **students** learn interactively through AI-driven tools.  
This project is developed as a **Final Year Project (FYP)** with a focus on modern web technologies and artificial intelligence.

---

##  Features

###  For Teachers
- **Assignment Generator** – Create customized assignments from uploaded documents
- **Quiz Generator** – Generate quizzes with multiple question types
- **PDF Generation** – Download assignments and solutions as PDF files
- **Proximity Detection** – Count students in classroom images using **YOLO**

###  For Students
- **Practice Questions** – AI-generated practice material
- **Flashcards** – Interactive learning cards
- **Speech-to-Text** – Voice-based input for answers
- **Text-to-Speech** – Audio generation for content
- **Progress Tracking** – Monitor learning performance
- **Review Mistakes** – Learn from previous errors

---

## 🧠 AI Capabilities
- Multiple AI providers (**OpenAI GPT-4**, **Google Gemini**)
- Fallback mechanisms for API failures
- Safe error handling and user-friendly feedback



## 🛠️ Tech Stack

### Frontend
- **React 18**
- **TypeScript**
- **Vite**

### Styling & UI
- **Tailwind CSS**
- **shadcn/ui**

### Backend & Auth
- **Supabase Authentication**
- **Supabase PostgreSQL Database**

### AI & Media
- **OpenAI GPT-4**
- **Google Gemini**
- **ElevenLabs Text-to-Speech**
- **Speech Recognition API**

### Deployment
- **Vercel / Netlify (Production Ready)**

---

## ⚙️ Environment Variables

Create a `.env.local` file and add:

```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

## 🔐 Security Checklist

-  No hardcoded API keys  
-  Environment-based logging (development only)  
-  Error boundaries for production  
-  Form validation & sanitization  
-  Proper CORS configuration  

---

## ⚡ Performance Optimization

-  Code splitting  
-  Lazy loading components  
-  Optimized images  
-  Loading & error states  
-  Bundle size warnings addressed  

---

## 🌐 Browser Compatibility

- Chrome  
- Firefox  
- Safari  
- Edge  

Additional Notes:
- Fully responsive (Mobile / Tablet)
- Accessibility features included
- Requires **ES2020+** browser support

---

##  CI/CD Deployment (Vercel – Recommended)

### Deployment Steps

1. Import the GitHub repository into **Vercel**
2. Set required environment variables in the Vercel dashboard
3. Push changes to the `main` branch for automatic deployment
4. Pull requests automatically generate preview URLs

### Deployment Configuration

- **Framework:** Vite  
- **Build Command:** `npm run build`  
- **Output Directory:** `dist`  
- **Node Version:** `18.x`  

### URLs

- **Production:** https://eduguide-ai.vercel.app  
- **Development:** http://localhost:5173  

---

##  Development Setup

### Clone the Repository

```bash
git clone <repository-url>
cd FYP
```

### Install Dependencies

```bash
npm install
```

### Start Development Server

```bash
npm run dev
```

### Production Build

```bash
npm run build
npm run preview
```

## 📁 Project Structure

```text
src/
├── components/         # Reusable UI components
│   ├── auth/           # Authentication components
│   ├── common/         # Common/shared components
│   ├── features/       # Feature-specific components
│   ├── icons/          # Custom icons
│   ├── layout/         # Layout components (Navbar, Sidebar, etc.)
│   └── ui/             # shadcn/ui components
├── context/            # React context providers
├── hooks/              # Custom React hooks
├── integrations/       # Third-party integrations (AI, APIs, services)
├── lib/                # Core libraries and utilities
├── pages/              # Application pages/routes
├── services/           # API and backend service handlers
└── utils/              # Helper and utility functions
```

## 📈 Future Enhancements

- Offline mode support
- Progressive Web App (PWA)
- Real-time collaboration
- Advanced analytics dashboard
- Multi-language support


## 📄 License
This project is licensed under the MIT License.
