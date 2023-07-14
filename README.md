# OMDB-Consumer-API

OMDB-Consumer-API is a Java project that allows you to consume the OMDB API for movies, perform movie queries, and generate JSON files for these queries. This application provides a convenient way to retrieve movie information from the OMDB database and store it in JSON format for further analysis or integration with other systems.

## Features

✨ Search for movies by title, year, or IMDB ID.

✨ Retrieve detailed information about a movie, including title, plot, ratings, cast, and more.

✨ Generate JSON files for the search results, making it easy to store and manipulate the data.

## Prerequisites
Before running this application, make sure you have the following software installed:

* Java Development Kit (JDK) 8 or later
* Apache Maven
* Git

## Getting Started
1. Clone the repository:

```
git clone https://github.com/your-username/OMDB-Consumer-API.git
```

2. Navigate to the project directory:

```
cd OMDB-Consumer-API
```

3. Build the project using Maven:

```
 mvn clean install
```

4. Run the application:

```
java -jar target/omdb-consumer-api.jar
```

## Usage
1. Enter the search criteria when prompted. You can search by title, year, or IMDB ID.

2. View the search results displayed on the console.

3. To generate a JSON file for the search results, select the provided option.

4. The JSON file will be saved in the current directory.

Contributing
Contributions are welcome! If you encounter any issues or want to enhance the application, feel free to open a pull request.

1. Fork the repository.

2. Create your feature branch:


``` 
git checkout -b feature/new-feature
```
3. Commit your changes:

``` 
git commit -am 'Add a new feature'
```
4. Push to the branch:

```
git push origin feature/new-feature
```
5. Open a pull request.

## Acknowledgments
This project utilizes the following libraries and APIs:

* OMDB API
* Gson
* Apache HttpClient
  
Feel free to explore and modify the code according to your needs.

Enjoy searching for movies! 🍿🎬
