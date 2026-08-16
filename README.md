# NoteVault 📝

A modern, feature-rich note-taking web application built with React, TypeScript, and Vite. NoteVault provides an intuitive and powerful platform for creating, managing, and organizing your notes with rich text editing, attachments, and seamless cloud synchronization.

![NoteVault Logo](<img width="82" height="78" alt="note app logo" src="https://github.com/user-attachments/assets/6d0369c0-6d8a-419d-a3e0-5d1efed255f3" />)


**Live Demo:** [https://notevaultapp-2.vercel.app](https://notevaultapp-2.vercel.app)

---

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage Guide](#usage-guide)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

---

## Project Description

NoteVault is a comprehensive note-taking application designed to help users organize, create, and manage their digital notes efficiently. Built with modern web technologies (React + TypeScript), it offers a rich text editing experience with support for media attachments, tables, and advanced note management features. The application provides a seamless user experience across all devices with a clean, intuitive interface and powerful organizational tools.

Whether you're a student, professional, or personal user, NoteVault helps you capture ideas, organize information, and maintain productivity with ease.

---

## Features

### Core Note Management
- ✨ **Rich Text Editor** - Advanced text formatting with execCommand-based utilities
- 📎 **File & Image Attachments** - Upload and embed files and images in your notes
- 📊 **Insertable Tables** - Create and manage tables within notes for organized data
- 📝 **Note CRUD Operations** - Create, read, update, soft-delete (trash), restore, and permanently delete notes
- 🗑️ **Trash & Recovery** - Soft delete notes to trash and restore them when needed
- 🔄 **Multi-Select & Bulk Actions** - Select multiple notes and perform batch operations

### User Experience
- 📱 **Fully Responsive Design** - Optimized for desktop, tablet, and mobile devices
- 🎨 **Modern UI/UX** - Clean, professional interface with smooth animations
- 🧭 **Sidebar Navigation** - Easy navigation with collapsible sidebar menu
- 🎯 **Intuitive Interface** - User-friendly controls and accessibility features
- 🌍 **Localization Support** - Multi-language support (English, Spanish, and more)
- ⚡ **Fast Performance** - Optimized loading and smooth interactions

### Authentication & Account
- 👤 **User Authentication** - Secure sign-in and sign-up functionality
- 📋 **Account Management** - Manage user profile and preferences
- 🔐 **Data Privacy** - Privacy policy and terms of service compliance

### Additional Features
- 💬 **Support & Contact** - Built-in support and contact modals
- 🎁 **Exclusive Features** - Premium note-taking capabilities
- 📲 **Cloud Synchronization** - Sync notes across devices (backend integration ready)
- 🏷️ **Note Organization** - Tag and categorize notes for better management
- 🔍 **Search Functionality** - Find notes quickly with search capability

---

## Technology Stack

### Frontend Framework
- **React 18.3.1** - UI library for building interactive components
- **TypeScript** - Type-safe JavaScript for robust development
- **Vite 6.3.5** - Fast build tool and development server

### UI & Styling
- **Radix UI** - Unstyled, accessible UI components library
  - Accordion, Alert Dialog, Avatar, Checkbox, Dialog, Dropdown Menu, and 20+ more primitives
- **MUI (Material-UI)** - Icons and additional component library
- **Tailwind CSS 4.1** - Utility-first CSS framework
- **Custom CSS** - Theme and styling customization

### State Management & Forms
- **React Hooks** - Modern state management approach
- **React Hook Form 7.55** - Efficient form handling

### Additional Libraries
- **React Router 7.13** - Client-side routing
- **React DnD 16** - Drag and drop functionality
- **Recharts 2.15** - Data visualization and charts
- **Date-fns 3.6** - Date manipulation utilities
- **Sonner 2.0** - Toast notifications
- **Canvas Confetti** - Celebration animations
- **Lucide React** - Beautiful icon library
- **Motion** - Animation library

### Development Tools
- **PostCSS 4** - CSS transformation
- **pnpm** - Fast, disk space efficient package manager

### Deployment
- **Vercel** - Hosting and continuous deployment platform

---

## Installation

### Prerequisites
- **Node.js** - Latest LTS version (v18.0.0 or higher)
- **pnpm** - Fast package manager (recommended)
  - Install via: `npm install -g pnpm`
  - Alternatively: `npm` or `yarn` can be used
- **Git** - For cloning the repository

### Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/tharunoffical054-png/NoteVault1.git
   cd NoteVault1
