# Personalized News Aggregator 📰

A Django-based web application that delivers personalized news articles to users based on their preferences.

## How to Run the Project

1. **Open Two PowerShell Windows**  
   Open two separate PowerShell terminals on your machine.

2. **Navigate to the Project Directory in Both**  
   Example:  
   cd C:\Users\<YourUsername>\Personalized-News-Aggregator

3. **Activate the Virtual Environment in Both**  
   In both terminals, run:  
   .\venv\Scripts\activate

4. **Fetch Latest News in the First Terminal**  
   In the first terminal, run:  
   python manage.py fetch_news

5. **Start the Server in the Second Terminal**  
   In the second terminal, run:  
   python manage.py runserver  
   The server will start and provide a link like:  
   http://127.0.0.1:8000/

6. **Access the Application in Your Browser**  
   Open your browser and navigate to:  
   http://127.0.0.1:8000/

## Admin Panel Access

The admin interface is available at:  
http://127.0.0.1:8000/admin/

To access it, create a superuser by running:  
python manage.py createsuperuser

## Features

- Personalized news feed based on user interests
- Admin panel for managing articles and users
- Real-time news fetching from sources

## License

This project is licensed under the MIT License.

## Contributions

Feel free to fork the repository and submit pull requests to improve the project.

## Contact

For questions or suggestions, please open an issue on this repository.
