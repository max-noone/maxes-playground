<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dashboard</title>
    <style>
        body {
            background-color: blue;
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
        }
        .search-container {
            position: absolute;
            top: 10px;
            right: 10px;
        }
        .search-container input[type="text"] {
            padding: 5px;
            font-size: 1em;
        }
        .search-container button {
            padding: 5px 10px;
            font-size: 1em;
            cursor: pointer;
        }
        .games-button {
            display: none;
            padding: 10px 20px;
            font-size: 1em;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="search-container">
        <input type="text" id="searchInput" placeholder="Search...">
        <button onclick="performSearch()">Search</button>
    </div>
    <h1>Welcome to the Dashboard</h1>
    <button id="cloaker" style="display:none;">Cloaker</button>
    <button id="gamesButton" class="games-button" onclick="location.href='ind4x.html'">Games</button>

    <script>
        function performSearch() {
            var query = document.getElementById("searchInput").value;
            if (query === "jet2holiday") {
                window.location.href = 'midload.html';
            } else if (query === "kevin hart") {
                window.location.href = '/dashboard/kevinhart.gif';
            } else if (query === "freddie") {
                window.location.href = '/dashboard/freddy.html';
                 } else if (query === "zach") {
                window.location.href = '/dashboard/zach.html';
                   } else if (query === "william") {
                window.location.href = '/dashboard/william.html';
                  } else if (query === "toby") {
                window.location.href = '/dashboard/toby.html';
                 } else if (query === "eliza") {
                window.location.href = '/dashboard/eliza.html';
                 } else if (query === "mrbean") {
                window.location.href = '/dashboard/mrbean.html';
                  } else if (query === "sully") {
                window.location.href = '/dashboard/sully.html';
                   } else if (query === "bophouse") {
                window.location.href = '/dashboard/bophouse.html';
                  } else if (query === "newkid") {
                window.location.href = '/dashboard/newkid.html';
            }
        }
    </script>
</body>
</html>
