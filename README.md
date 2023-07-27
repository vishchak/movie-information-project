# Movie Information Project

The Movie Information Project is a web application that allows users to browse and view details of various movies. It retrieves movie data from an XML file and dynamically displays the information on the webpage using JavaScript.

## Features

- Display a list of movies with their titles, release years, directors, genres, ratings, and descriptions.
- Show the movie posters for each movie, enhancing the visual experience.
- Apply a fancy styling theme to enhance the overall design.

## Getting Started

To get started with the Movie Information Project, follow these steps:

1. Clone the repository:git clone https://github.com/vishchak/movie-information-project.git

2. Open the `movies.html` file in your web browser to view the movie information.

## Usage

- Browse through the list of movies to find details such as title, year, director, genre, and rating.
- Click on a movie poster to view its description.
- Hover over the table rows for a subtle visual effect.

## Movie Data Format

The movie data is stored in an XML file (`movie.xml`) following the below structure:

```xml
<!-- XML structure example -->
<movies>
    <movie id="1">
        <title>Title of the Movie</title>
        <original_title>Original Title (if applicable)</original_title>
        <!-- Other movie details such as year, director, genre, rating, description, duration, language, country, cast, and poster -->
    </movie>
    <!-- Additional movie entries -->
</movies>
```

Contributing
Contributions to the Movie Information Project are welcome! If you find any issues or have suggestions for improvements, please feel free to open a new issue or submit a pull request.

License
The Movie Information Project is licensed under the MIT License.