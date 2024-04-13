<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vatsal's Website</title>
</head>
<body>
    <h1 id="name">Vatsal</h1>
    <p id="description"></p>

    <script>
        // Function to change the description when the name is clicked
        document.getElementById("name").addEventListener("click", function() {
            document.getElementById("description").innerText = "He is a Good Deed";
        });
    </script>
</body>
</html>
