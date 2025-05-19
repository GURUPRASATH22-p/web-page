<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Boxes</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <div class="box top-box">
            <h2>Box 1</h2>
            <div class="options" id="top-options">
                <label>Color:</label>
                <select id="top-color">
                    <option value="red">Red</option>
                    <option value="blue">Blue</option>
                    <option value="green">Green</option>
                </select>
                <label>Size:</label>
                <select id="top-size">
                    <option value="small">Small</option>
                    <option value="medium">Medium</option>
                    <option value="large">Large</option>
                </select>
            </div>
        </div>
        <div class="box middle-box">
            <h2>Box 2</h2>
            <div class="options" id="middle-options">
                <label>Color:</label>
                <select id="middle-color">
                    <option value="red">Red</option>
                    <option value="blue">Blue</option>
                    <option value="green">Green</option>
                </select>
                <label>Size:</label>
                <select id="middle-size">
                    <option value="small">Small</option>
                    <option value="medium">Medium</option>
                    <option value="large">Large</option>
                </select>
            </div>
        </div>
        <div class="box bottom-box">
            <h2>Box 3</h2>
            <div class="options" id="bottom-options">
                <label>Color:</label>
                <select id="bottom-color">
                    <option value="red">Red</option>
                    <option value="blue">Blue</option>
                    <option value="green">Green</option>
                </select>
                <label>Size:</label>
                <select id="bottom-size">
                    <option value="small">Small</option>
                    <option value="medium">Medium</option>
                    <option value="large">Large</option>
                </select>
            </div>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
