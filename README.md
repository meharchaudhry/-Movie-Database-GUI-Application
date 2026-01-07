# Movie-Database-GUI-Application

This project is a Python-based graphical user interface (GUI) application built using **Tkinter** and **MySQL** that allows users to explore, filter, and analyze a movie database interactively. The application supports predefined analytical queries, advanced filtering, and free-text search across movie attributes.

## Features
- Interactive GUI for querying a movie database
- Predefined analytical queries (ratings, revenue, genres, seasonal trends, ROI, etc.)
- Advanced filtering by genre, language, runtime, vote average, and adult content
- Movie search by title
- Tabular result display using Treeview
- Integrated image-based welcome screen

## Analytical Capabilities
- Top-rated and highest-grossing movies
- Genre-wise movie distribution
- Seasonal and monthly revenue analysis
- Runtime vs popularity analysis
- ROI and budget-performance insights
- Language and animation-specific trends

## Tech Stack
- Python
- Tkinter (GUI)
- MySQL
- SQL
- PIL (Image handling)

## Database Structure
The application expects a MySQL database containing a `movies` table with fields such as:
- title
- genres
- runtime
- revenue
- budget
- release_date
- voteaverage
- popularity
- spokenlanguages
- productioncompanies
- overview

## Setup Instructions
1. Clone the repository
   ```bash
   git clone https://github.com/your-username/movie-database-gui-application.git
