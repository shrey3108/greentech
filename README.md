# EcoTrack+ - Smart Energy & Sustainability Platform

A comprehensive platform for energy monitoring, waste management, and sustainable living.

## Features

- Real-time energy usage monitoring
- Waste segregation tracking
- Food waste management
- Carbon footprint calculator
- Environmental impact dashboard
- AI-powered recommendations


## Technology Stack:

<img src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white"/> <img src="https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/> <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white"/>  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
 <img src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white"/> 


## 🛠️ Technology Stack

### Backend
- **Framework**: Python Flask
- **Database**: MongoDB
- **AI/ML**: Google Gemini AI, scikit-learn
- **Authentication**: JWT

### Frontend
- **Framework**: HTML5, CSS3, JavaScript
- **Responsive Design**: Bootstrap
- **Interactive UI**: jQuery, AJAX

### How to Get Started?
## 📋 Prerequisites

- Python 3.8 or higher
- MongoDB
- Google API Key for Gemini AI
- Required Python packages (listed in requirements.txt)

## 🚀 Deployment

## Local Development

1. Clone the repository
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Set up environment variables in `.env`:
   ```
   MONGODB_URI=your_mongodb_uri
   GOOGLE_API_KEY=your_google_api_key
   SECRET_KEY=your_secret_key
   ```
5. Run the application:
   ```bash
   python app.py
   ```

## Deployment to Render

1. Create a new Web Service on Render
2. Connect your GitHub repository
3. Use the following settings:
   - Environment: Python
   - Build Command: `pip install -r requirements.txt`
   - Start Command: `gunicorn app:app`
4. Add environment variables:
   - `MONGODB_URI`: Your MongoDB Atlas connection string
   - `GOOGLE_API_KEY`: Your Google API key
   - `SECRET_KEY`: A secure random string

## Environment Variables

- `MONGODB_URI`: MongoDB connection string
- `GOOGLE_API_KEY`: Google API key for AI features
- `SECRET_KEY`: Flask secret key for session management

## Project Structure

```
.
├── app.py              # Main application file
├── requirements.txt    # Python dependencies
├── gunicorn.conf.py   # Gunicorn configuration
├── render.yaml        # Render deployment configuration
├── .env              # Environment variables (local development)
├── .gitignore        # Git ignore rules
└── templates/        # HTML templates
    ├── base.html
    ├── index.html
    ├── energy_monitor.html
    └── ...
#### GitHub Repository Structure


## Team Members:

| S.No. | Name | Role | GitHub Username:octocat: |
| --------------- | --------------- | --------------- | --------------- |
| 1. | Shrey Shukla | Backend  Development| [@shrey3108](https://github.com/shrey3108)  |
| 2. | Prasham Shah| 	Frontend+ML  Development | [@Prasham0105](https://github.com/prasham0105)  |

## Maintainers✨

<table>
  <tbody><tr>
    <td align="center"><a href="https://github.com/shrey3108"><img alt="" src="https://avatars.githubusercontent.com/shrey3108" width="100px;"><br><sub><b>Shrey Shukla</b></sub></a><br><a href="https://github.com/shrey3108/greentech" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/prasham0105"><img alt="" src="https://avatars.githubusercontent.com/prasham0105" width="100px;"><br><sub><b> Prasham Shah </b></sub></a><br><a href="https://github.com/shrey3108/greentech" title="Code">💻</a></td>

  </tr>
</tbody></table>


# License :memo:

This project follows the [MIT License](https://choosealicense.com/licenses/mit/).

[![Uses Git](https://forthebadge.com/images/badges/uses-git.svg)](https://github.com/rudrakshi99/Farmer-Call-Center) 
[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://github.com/rudrakshi99/Farmer-Call-Center)
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://github.com/rudrakshi99/Farmer-Call-Center)
[![Built with love](https://forthebadge.com/images/badges/built-with-love.svg)](https://github.com/rudrakshi99/Farmer-Call-Center.git) [![Built By Developers](https://forthebadge.com/images/badges/built-by-developers.svg)](https://github.com/rudrakshi99/Farmer-Call-Center) 
