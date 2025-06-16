# DressColorAnalyzer
An AI-powered web application that analyzes colors in dress images and provides personalized accessory suggestions.

## Features

- **Color Analysis**: Extract dominant colors from dress images using advanced computer vision
- **Smart Suggestions**: Get personalized recommendations for jewelry, bags, shoes, and scarves
- **User Accounts**: Register, login, and track your analysis history
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **History Tracking**: Save and revisit previous color analyses

## Tech Stack

- **Backend**: Python Flask with SQLAlchemy ORM
- **Frontend**: Bootstrap 5 with dark theme, vanilla JavaScript
- **Database**: PostgreSQL
- **Image Processing**: PIL (Pillow) and ColorThief
- **Authentication**: Session-based with password hashing

## Quick Deploy

### Deploy to Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/your-username/dress-color-analyzer)

### Deploy to Railway
1. Fork this repository
2. Connect to Railway
3. Deploy automatically

### Deploy to Render
1. Fork this repository
2. Create new Web Service on Render
3. Connect your GitHub repo
4. Use these settings:
   - Build Command: `pip install -r requirements.txt`
   - Start Command: `gunicorn --bind 0.0.0.0:$PORT main:app`

## Local Development

1. Clone the repository:
```bash
git clone https://github.com/your-username/dress-color-analyzer.git
cd dress-color-analyzer
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set environment variables:
```bash
export SESSION_SECRET="your-secret-key"
export DATABASE_URL="postgresql://user:password@localhost/dbname"
```

4. Run the application:
```bash
python main.py
```

## Environment Variables

- `SESSION_SECRET`: Secret key for Flask sessions
- `DATABASE_URL`: PostgreSQL database connection string

## Usage

1. Register for an account or login
2. Upload a photo of your dress
3. View the extracted color palette
4. Get personalized accessory suggestions
5. Save your analysis to history

## License

MIT License - feel free to use and modify for your projects.
