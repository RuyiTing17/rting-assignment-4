# LSA Search Engine

This project implements a simple search engine using Latent Semantic Analysis (LSA) on the 20 Newsgroups dataset.

## Setup and Running

1. Ensure you have Python 3.8+ installed.
2. Clone this repository:
   ```
   git clone <your-repo-url>
   cd <your-repo-directory>
   ```
3. Install dependencies:
   ```
   make install
   ```
4. Run the application:
   ```
   make run
   ```
5. Open a web browser and navigate to `http://localhost:3000`

## Usage

Enter a search query in the input field and click "Search". The application will display the top 5 most relevant documents along with their similarity scores and a bar chart visualization.

## Files

- `app.py`: Backend Flask application with LSA implementation
- `index.html`: Frontend HTML/CSS/JavaScript
- `Makefile`: Commands for setup and running
- `.github/workflows/python-app.yml`: GitHub Actions workflow
- `requirements.txt`: Python dependencies