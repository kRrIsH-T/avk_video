# Slideshow Video Maker
This is a web application that allows users to turn their images into memorable videos with background music, transitions, and more. Users can upload images, set durations, choose music and transitions, and generate a video slideshow.

## Features

- User registration and login
- Image upload and management
- Set custom durations for each image
- Choose from multiple background music tracks
- Select video transitions (crossfade, slide, etc.)
- Adjustable video resolution and quality
- Admin dashboard for user and image stats
- Download generated videos

## Tech Stack

- **Backend:** Python, Flask, psycopg2 (CockroachDB)
- **Frontend:** HTML, CSS, JavaScript (Jinja2 templates)
- **Video Processing:** [moviepy](https://github.com/Zulko/moviepy)
- **Database:** CockroachDB

## Setup Instructions

1. **Clone the repository:**
   ```sh
   git clone <repo-url>
   cd code

## Install Dependencies

```sh
pip install -r requirements.txt
```
## Set up the database
- Ensure CockroachDB is running and accessible
- Update credentials in app.py if needed

## Run the application
```sh
python app.py
```

## File Structure
- app.py - Main Flask application
- maker.py - Video creation logic
- transitions.py - Custom video transitions
- templates/ - HTML templates (Jinja2)
- static/ - Static files (CSS, JS, images, audio)
- requirements.txt - Python dependencies

## Usage
1. Register or log in.
2. Upload your images.
3. Set the duration for each image.
4. Choose background music and transitions.
5. Click "Create Video" to generate your slideshow.
6. Download your video from the workspace.