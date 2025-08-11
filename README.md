# Medlife AI Project

## Overview

This project consists of a React frontend and a FastAPI backend for Medlife AI, a healthcare assistant platform.

## Frontend

- Built with React.
- Features include user authentication, chat interface with AI providers, API key management, member management, and PDF export.
- API keys for multiple AI providers can be managed in the settings.
- Uses React Router for navigation and protected routes.

## Backend

- Built with FastAPI.
- Provides REST API endpoints for user management, chat processing, and member data.
- Uses SQLite database for persistence.
- Supports multiple AI providers with API key management.

## Setup Instructions

### Backend

1. Create and activate a Python virtual environment.
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Run the backend server:
   ```
   uvicorn app:app --reload
   ```

### Frontend

1. Install Node.js and npm.
2. Install dependencies:
   ```
   npm install
   ```
3. Start the development server:
   ```
   npm start
   ```

## Notes

- API keys are stored securely in browser localStorage.
- The chat interface disables input until a valid API key is provided.
- The settings modal allows managing multiple API keys with visual indicators.
- Backend and frontend code cleanup has been performed to remove unused code.

## Testing

- Test user authentication flows.
- Test chat interface with different AI providers.
- Test API key management and persistence.
- Test member management features.
- Test PDF export functionality.

## Contact

For issues or contributions, please contact the project maintainer.
