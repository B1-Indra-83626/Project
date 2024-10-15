**Overview**  
This project implements a **book recommendation system** using both **content-based** and **popularity-based** filtering approaches. Additionally, a **Flask web application** serves as the frontend for the recommendations. To enhance the dataset, a **web scraping script** is provided to collect book details from the **Goodreads website** using **Selenium**.



**Features**  
1. **Content-Based Filtering**  
   - Recommends books similar to the input based on features such as author,title and description.  
   - Implemented in `content based.ipynb`.

2. **Popularity-Based Filtering**  
   - Recommends the most popular and highly rated books from the dataset.  
   - Implemented in `popularity based.ipynb`.

3. **Web Scraping for Data Enrichment**  
   - `scrap.py` extracts book details from the **Goodreads website** using **Selenium**.  
   - It collects information such as book titles, authors, and ratings.  
   - You can customize the script to gather additional relevant data for recommendations.

4. **Flask Web Application**  
   - A simple interactive web interface to access the recommendation engine.  
   - Located in the `flask project/` directory, with `app.py` handling backend logic and HTML templates for the frontend.

---

**Setup and Installation**  

1. **Clone the Repository**  
   ```bash
   git clone <repository_url>
   cd Project-main/project/flask project

