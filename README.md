
# Spotify Clone

A full-stack Spotify clone built with Next.js 14, React, Tailwind CSS, Supabase, and PostgreSQL. This project demonstrates modern web development practices by recreating Spotify's core features and functionality.


## 🎵 Features

- **Authentication**
  - Credential authentication using Supabase
  - Github authentication integration
  - Secure user management

- **Music Playback**
  - Song upload and streaming
  - Advanced audio player controls
  - Favorites/Liked songs functionality
  - Real-time playback updates

- **User Interface**
  - Responsive design for all devices
  - Tailwind CSS styling
  - Smooth animations and transitions
  - Modern and intuitive layout

- **Backend Integration**
  - Supabase and PostgreSQL database
  - File and image upload via Supabase storage
  - Efficient data fetching in server components
  - Real-time data synchronization

- **Form Handling**
  - Client-side form validation with react-hook-form
  - Error handling with react-toast
  - Seamless data submission

## 🚀 Tech Stack

- **Frontend**
  - Next.js 13.4
  - React
  - Tailwind CSS
  - TypeScript

- **Backend**
  - Supabase
  - PostgreSQL
  - Next.js API Routes

- **Authentication**
  - Google OAuth
  - Github OAuth

- **Storage**
  - Supabase Storage

## 💻 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/spotify-clone.git
   cd spotify-clone
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env.local
   ```
   Fill in your Supabase and other required credentials.

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:3000`

## 📄 Environment Variables

Create a `.env.local` file with the following variables:
```plaintext
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
SUPABASE_SERVICE_ROLE_KEY=your_service_role_key
```

## 🙏 Acknowledgments

- Inspired by Spotify's user interface and functionality
- Built following modern web development best practices
- Special thanks to the Next.js, Supabase, and Tailwind CSS communities

## ⚠️ Disclaimer

This is a demo project for educational purposes only. It is not affiliated with Spotify or intended for commercial use.
