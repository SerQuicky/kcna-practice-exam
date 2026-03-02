# KCNA Practice Exam

An interactive, browser-based KCNA practice exam app with two modes:
- **Exam Mode** (timed, scored at the end)
- **Practice Mode** (instant feedback with explanations)

## Live Demo

The app is available on GitHub Pages:

https://serquicky.github.io/kcna-practice-exam/

## Features

- Random question selection from the full question pool
- Domain/topic selection before starting
- Timer and progress tracking
- Question navigation with flag-for-review support
- Results screen with score, pass/fail, and answer review
- KCNA logo in the header, start screen, and favicon

## Project Structure

- `index.html` - base page structure
- `styles.css` - full styling
- `app.js` - full application logic
- `questions-data.js` - question pool
- `images/kcna-logo.png` - KCNA logo

## Run Locally

Since this is a static project, a simple HTTP server is enough:

```bash
cd /Users/michael.frank/Desktop/kcna-practice-exam
python3 -m http.server 8000
```

Then open in your browser:

http://localhost:8000

## Deploy to GitHub Pages

1. Commit and push your changes:
   - `git add .`
   - `git commit -m "Update app"`
   - `git push`
2. In GitHub, go to `Settings -> Pages`
3. Set **Source** to `Deploy from a branch`
4. Select branch `main` and folder `/(root)`
5. Save and wait a moment for deployment