<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Habit Tracker</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Habit Tracker</h1>
        <p>Track your habits visually and efficiently!</p>
    </header>
    
    <main>
        <section id="tracker">
            <h2>Your Habits</h2>
            <div id="habits-container">
                <!-- Habit grids will be dynamically generated here -->
            </div>
            <button id="add-habit-btn">Add Habit</button>
        </section>

        <section id="graph">
            <h2>Progress Graphs</h2>
            <canvas id="progressChart"></canvas>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Habit Tracker</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <script src="script.js"></script>
</body>
</html>
