<!DOCTYPE html>
<html lang='en'>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel='stylesheet' href="style.css"> </link>
    <title>Excuse Generator</title>
    <script type='text/javascript' src='index.js'> </script>
    <!-- <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@500&display=swap" rel="stylesheet"> -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@500&family=Oswald&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <h1>The World Is Ending</h1>
        <h2>feel free to excuse yourself</h2>
    </header>
    <div id="category-buttons">
        <button id="family-button">Family</button>
        <button id="office-button">Office</button>
        <button id="children-button">Children</button>
        <button id="college-button">College</button>
        <button id="party-button">Party</button>
    </div>
    <div id="excuses-list">
        <ul></ul>
    </div>
    <footer>
        <div id="hover-button">
            <button id="random-excuse">Hover for a Random Excuse</button><br>
        </div>
        <div id="form-area">
            <form id="new_excuse_form">
                <label for="dropDownPriority"></label>
                <br>
                <select name="Priority" id="dropDown">
                    <option value="" disabled selected>Select a category</option>
                    <option id="family-option" value="family">Family</option>
                    <option id="office-option" value="office">Office</option>
                    <option id="children-option" value="children">Children</option>
                    <option id="college-option" value="college">College</option>
                    <option id="party-option" value="party">Party</option>
                </select><br>
                <input id="new-excuse-text" type="text" name="new excuse"
                placeholder="enter excuse here"></input><br>
                <button id="submit-excuse">Submit New Excuse</button><br>
            </form>    
        </div>
    </footer>
</body>
</html>
