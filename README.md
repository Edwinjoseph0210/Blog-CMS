# Blog-CMS

A simple blog content management system built with Flask and SQLite.

## Features
- Create, view, and list blog posts
- Simple web interface
- SQLite database backend

## Project Structure
```
.
├── app.py
├── requirements.txt
├── schema.sql
└── templates/
    ├── create.html
    ├── index.html
    └── post.html
```

## Setup Instructions

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Edwinjoseph0210/Blog-CMS.git
   cd Blog-CMS
   ```

2. **Create a virtual environment (optional but recommended):**
   ```sh
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

4. **Set up the database:**
   ```sh
   sqlite3 database.db < schema.sql
   ```

5. **Run the application:**
   ```sh
   python app.py
   ```
   The app will be available at [http://127.0.0.1:5000](http://127.0.0.1:5000)

## Usage
- Visit the home page to see all posts.
- Click on a post title to view its content.
- Use the "Create" page to add a new post.

## License
This project is open source and available under the [MIT License](LICENSE).
