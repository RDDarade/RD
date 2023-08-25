# RD
<br>
My first Repo
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Movie Ticket Booking</title>
    <style>
        body {
          font-family: Arial, sans-serif;
          margin: 0;
          padding: 0;
        }
        header {
          background-color: #333;
          color: white;
          text-align: center;
          padding: 10px;
        }
        .container {
          max-width: 1200px;
          margin: 0 auto;
          padding: 20px;
        }
        .movie-card {
          border: 1px solid #ddd;
          padding: 10px;
          margin: 10px;
          display: inline-block;
          width: calc(33.33% - 20px);
          box-sizing: border-box;
          vertical-align: top;
        }
        .movie-image {
          width: 100%;
          max-height: 300px;
          object-fit: cover;
        }
        .movie-title {
          margin: 10px 0;
          font-weight: bold;
        }
        .booking-button {
          background-color: #f44336;
          color: white;
          border: none;
          padding: 5px 10px;
          cursor: pointer;
        }
    </style>
</head>

<body>
    <header>
        <h1>Movie Ticket Booking</h1>
    </header>
    <div class="container">
        <div class="movie-card">
            <img class="movie-image" src="movie1.jpg" alt="Movie 1">
            <h2 class="movie-title">Movie 1</h2>
            <button class="booking-button">Book Now</button>
        </div>
        <div class="movie-card">
            <img class="movie-image" src="movie2.jpg" alt="Movie 2">
            <h2 class="movie-title">Movie 2</h2>
            <button class="booking-button">Book Now</button>
        </div>
        <div class="movie-card">
            <img class="movie-image" src="movie3.jpg" alt="Movie 3">
            <h2 class="movie-title">Movie 3</h2>
            <button class="booking-button">Book Now</button>
        </div>
    </div>
</body>

</html>
