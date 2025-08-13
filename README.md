Link Saver + Auto-Summary
A modern full-stack web application for saving and organizing bookmarks with automatic content summarization. Built for the SDE Internship take-home assignment.

🚀 Live Demo
View Live Demo ← Replace with your actual demo URL
✨ Features


🔐 Authentication System

Email/password registration and login
Password hashing with bcrypt-equivalent security
Persistent session management with JWT-like tokens
Secure local storage of user data


🔖 Bookmark Management

Save any URL with automatic metadata extraction
Fetch page titles and favicons automatically
Auto-generated summaries using Jina AI free API
Duplicate URL prevention per user


📱 Responsive Interface

Modern glassmorphism design with backdrop blur effects
Responsive grid layout (desktop, tablet, mobile)
Interactive bookmark cards with hover effects
Delete functionality with confirmation



Nice-to-Have Features ✅

🌙 Dark Mode Toggle - Persistent theme switching with smooth transitions
🎯 Drag & Drop Reordering - Rearrange bookmarks with visual feedback
📖 Expandable Summaries - Click to show more/less summary text
⚡ Real-time Feedback - Loading states, success/error notifications
🎨 Modern UX - Smooth animations, micro-interactions, empty states

🛠 Tech Stack
Frontend

HTML5 - Semantic markup and structure
CSS3 - Modern styling with Grid, Flexbox, animations
Vanilla JavaScript (ES6+) - No frameworks, pure modern JS
localStorage - Client-side data persistence

Backend Logic

AuthService Class - User authentication and session management
BookmarkService Class - Bookmark CRUD operations and API integration
Client-side Architecture - No server required for demo

External APIs

Jina AI API (r.jina.ai) - Free content summarization (no API key required)
Google Favicon API - Website icon extraction
URL Metadata Extraction - Automatic title and favicon fetching

Database

Browser localStorage - Persistent client-side storage
JSON-based data structure - User accounts and bookmarks
Per-user data isolation - Secure data separation
