# Mechascape
**Project for HackNJIT 2024**

## Overview
**Mechascape** is an AI-powered tool for creating, modifying, and visualizing steampunk-inspired blueprints and 3D models through a user-friendly interface.

## Technology Stack

### Frontend
- **React.js**: Component-based framework for the UI.
- **TailwindCSS**: Utility-first CSS for styling.
- **Fabric.js**: Canvas rendering for interactive blueprint editing.

### Backend
- **FastAPI + Uvicorn**: Python-based backend for handling API routes, ML, and image processing.

### Image Processing and 3D Modeling
- **OpenCV**: Advanced image processing.
- **Pillow**: Basic image handling.
- **Trimesh**: 3D model generation in OBJ format.

### Machine Learning
- **PyTorch**: Core ML framework.
- **Transformers**: NLP for generating blueprint descriptions.

### Database
- **MongoDB (Atlas)**: Cloud database for storing user data and blueprints.

### User Authentication and Login
- **JWT (JSON Web Tokens)**: Token-based authentication for secure user login and route protection.
- **OAuth2 (FastAPI)**: Manages token generation and user credential verification.
- **Passlib**: Password hashing and verification for secure user data handling.

## Key Features
- **AI-Powered Blueprint Creation**: Generate unique designs with ML models.
- **Interactive Editing**: Real-time blueprint customization.
- **3D Model Export**: Save designs as OBJ files.
- **User Authentication**: Secure login system with JWT-based access tokens.
- **Comprehensive API**: FastAPI ensures smooth backend/frontend integration.
