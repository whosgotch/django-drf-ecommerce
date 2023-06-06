# Django DRF Ecommerce Project
This is a Django-based ecommerce project built using Django Rest Framework (DRF). It provides a backend API for managing various ecommerce functionalities such as product listing, shopping cart, order management, and user authentication.

## Functionality
- Product Listing: The project allows listing and searching for products.
- API Endpoints: The ecommerce functionalities are exposed via API endpoints, making it easy to integrate with frontend or other systems.
- Documentation: The project includes comprehensive documentation to assist with development, customization, and integration.

## Technologies Used
- Python 3.11
- Django 4.2
- Django Rest Framework
- Factoryboy
- Pytest

## Prerequisites
Make sure you have the following installed before proceeding:
- Python 3.9 or above

## Setup and Installation
1. Clone the repository:
```
git clone
```
2. Create a virtual environment:
```
python -m venv env
```
3. Activate the virtual environment:
*For Windows:*
```
venv\Scripts\activate
```
*For macOS/Linux:*
```
source venv/bin/activate
```
4. Install the project dependencies:
```
pip install -r requirements.txt
```
5. Apply database migrations:
```
python manage.py migrate
```
6. Start the development server:
```
python manage.py runserver
```
Access the application in your web browser at http://localhost:8000.

## Testing
To run the tests for the Django Blog project, execute the following command:
```
pytest
```
The tests utilize Pytest and Factoryboy to ensure the functionality is working as expected and to maintain code quality.

## Documentation 
For detailed documentation on how to use and customize the project, please refer to the Documentation file.
