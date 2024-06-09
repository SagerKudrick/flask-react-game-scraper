# Dynamic Card Manager

This application combines the power of Flask, React, and Python to create, update, and delete cards. On first run, a predefined website is scraped to populate our database with latest games, which you can filter based on whether they're free or paid.

## Technologies Used

- **Backend**: Flask is utilized to power the API endpoints, providing a robust backend infrastructure for handling data requests. SQLAlchemy is used for database management.
- **Frontend**: React takes the lead in crafting an intuitive and interactive user interface, ensuring a smooth experience for users.

## Features

### Create Dynamic Cards
<p align="center">
  <img src="https://github.com/SagerKudrick/flask-react-game-scraper/blob/main/readme-images/creating.gif">
</p>

Python scripts scrape data from a designated website, populating our database with the latest information, but you can also add your own. 

### Update Dynamic Cards
<p align="center">
  <img src="https://github.com/SagerKudrick/flask-react-game-scraper/blob/main/readme-images/update.gif">
</p>

Keep your cards up to date with the latest information.

### Delete Dynamic Cards
<p align="center">
  <img src="https://github.com/SagerKudrick/flask-react-game-scraper/blob/main/readme-images/delete.gif">
</p>

Delete functionality ensures a clutter-free experience.

### Filter Cards
<p align="center">
  <img src="https://github.com/SagerKudrick/flask-react-game-scraper/blob/main/readme-images/filtering.gif">
</p>

See only relevant cards, filtering based on whether a game is "Free" or "Paid".
