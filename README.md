ClauseLens

AI-Powered Document Analysis Tool
A hackathon project that integrates Clause.ai’s AI-generated frontend with Kiro’s backend starter code to analyze and extract insights from documents.


Table of Contents


*Project Overview
*Features
*Installation
*Usage
*Folder Structure
*Contributing
*License

Project Overview

ClauseLens allows users to upload documents and receive AI-driven analysis, highlighting important clauses and insights. The frontend is generated using Clause.ai, while the backend is structured with Kiro for modularity and easy expansion.

Features

*Upload and analyze documents in multiple formats (PDF, DOCX, TXT)
*AI-powered clause extraction and summarization
*User-friendly frontend with interactive display
*Modular backend architecture for adding new AI features easily

Installation

1. Clone the repository
 git clone <your-repo-link>
 cd ClauseLens

2. Install frontend dependencies:
 cd frontend
 npm install

3. Install backend dependencies:
 cd ../backend
 npm install

4.Set up environment variables (if needed) in a .env file:
 API_KEY=<your_clause_ai_api_key>
 PORT=5000

 Usage:
  Run Frontend
  cd frontend
  npm start
  Run Backend
  cd backend
  npm start

Folder Structure:
ClauseLens/
├─ frontend/        
├─ backend/         
├─ architecture/    
├─ docs/            
└─ .kiro/           

Contributing:
Fork → Branch → Commit → Pull Request

License:
MIT
 

 




