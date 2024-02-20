# FastAPI User Token Authenticator API
![FastAPI_b](https://github.com/AbinandhMJ/FastAPI-TokenAuthenticator-API/assets/99226172/72f96365-27c7-4421-8055-205c02291d8f)


This is a simple example of implementing token-based authentication in a FastAPI application.


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

To run this project, you need Python installed on your machine. You can download it from [python.org](https://www.python.org/downloads/).

### Installing

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/AbinandhMJ/FastAPI-TokenAuthenticator-API.git
   ```

2. Navigate into the project directory:

   ```
   cd FastAPI-TokenAuthenticator-API
   ```

3. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

### Running the Application

To run the FastAPI application, execute the following command:

```
uvicorn main:app --reload
```

The API will start running at `http://localhost:8000`.
Testing Port will be `http://localhost:8000/docs` 

### Endpoints

- `/token`: Issue an access token by providing valid credentials.
- `/users/me/`: Get information about the currently authenticated user.
- `/users/me/items`: Get items belonging to the currently authenticated user.

## Built With

- [FastAPI](https://fastapi.tiangolo.com/) - FastAPI framework for building APIs with Python 3.7+.
- [Pydantic](https://pydantic-docs.helpmanual.io/) - Data validation and settings management using Python type annotations.
- [Passlib](https://passlib.readthedocs.io/en/stable/) - Password hashing library.
- [JWT](https://jwt.io/) - JSON Web Tokens for token-based authentication.

## Authors

- [Abinandh MJ](https://github.com/AbinandhMJ) - *Initial work*

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Hat tip to anyone whose code was used
- Inspiration
- etc.
