# HTML-ACT-1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML ACT 1 </title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            margin: 0;
            padding: 20px;
            text-align: center;
        }

        h1 {
            color: #333;
        }

        .team {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .member {
            background-color: white;
            width: 250px;
            padding: 20px;
            border-radius: 10px;
        }

        .member img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
        }

        .member h2 {
            margin-bottom: 5px;
        }

        .member p {
            color: #555;
        }
    </style>
</head>

<body>

    <h1> Group 3 </h1>
    <p>Get to know our team members.</p>

    <div class="team">

        <div class="member">
            <img src="james.jpeg.jpg" alt="Member 1">
            <h2>James Carl Junio</h2>
            <h3>Student</h3>
            <p>Age: 24</p>
            <p>Course and section: BSIT3K</p>
            <p>Hobby: Playing Online games</p>
            <p>About Me: I'm the Guild Master of the Honor of Kings division of PLMUN Celestial Esports..</p>
        </div>

        <div class="member">
            <img src="peter parker.jpg" alt="Member 2">
            <h2>Peter Parker</h2>
            <h3>Student</h3>
            <p>Age: 20</p>
            <p>Course and section: BSIT3K</p>
            <p>Hobby: photography</p>
            <p>About Me: I have superpowers.</p>
        </div>

        
    </div>

</body>
</html>
