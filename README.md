# Me
"My personal corner of the internet, showcasing projects and skills."
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Tic Tac Toe</title>

<style>
body {
    font-family: Arial, sans-serif;
    background: #222;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.game {
    display: grid;
    grid-template-columns: repeat(3, 100px);
    gap: 5px;
}

.cell {
    width: 100px;
    height: 100px;
    background: #fff;
    position: relative;
}

input {
    display: none;
}

label {
    width: 100%;
    height: 100%;
    display: block;
    cursor: pointer;
}

/* X */
input:nth-child(1):checked + label::before,
input:nth-child(3):checked + label::before,
input:nth-child(5):checked + label::before,
input:nth-child(7):checked + label::before,
input:nth-child(9):checked + label::before {
    content: "X";
    color: red;
}

/* O */
input:nth-child(2):checked + label::before,
input:nth-child(4):checked + label::before,
input:nth-child(6):checked + label::before,
input:nth-child(8):checked + label::before {
    content: "O";
    color: blue;
}

label::before {
    font-size: 60px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
</style>
</head>

<body>

<div class="game">
    <div class="cell">
        <input type="radio" name="c1" id="c1x">
        <label for="c1x"></label>
        <input type="radio" name="c1" id="c1o">
        <label for="c1o"></label>
    </div>

    <div class="cell">
        <input type="radio" name="c2" id="c2x">
        <label for="c2x"></label>
        <input type="radio" name="c2" id="c2o">
        <label for="c2o"></label>
    </div>

    <div class="cell">
        <input type="radio" name="c3" id="c3x">
        <label for="c3x"></label>
        <input type="radio" name="c3" id="c3o">
        <label for="c3o"></label>
    </div>

    <div class="cell">
        <input type="radio" name="c4" id="c4x">
        <label for="c4x"></label>
        <input type="radio" name="c4" id="c4o">
        <label for="c4o"></label>
    </div>

    <div class="cell">
        <input type="radio" name="c5" id="c5x">
        <label for="c5x"></label>
        <input type="radio" name="c5" id="c5o">
        <label for="c5o"></label>
    </div>

    <div class="cell">
        <input type="radio" name="c6" id="c6x">
        <label for="c6x"></label>
        <input type="radio" name="c6" id="c6o">
        <label for="c6o"></label>
    </div>

    <div class="cell">
        <input type="radio" name="c7" id="c7x">
        <label for="c7x"></label>
        <input type="radio" name="c7" id="c7o">
        <label for="c7o"></label>
    </div>

    <div class="cell">
        <input type="radio" name="c8" id="c8x">
        <label for="c8x"></label>
        <input type="radio" name="c8" id="c8o">
        <label for="c8o"></label>
    </div>

    <div class="cell">
        <input type="radio" name="c9" id="c9x">
        <label for="c9x"></label>
        <input type="radio" name="c9" id="c9o">
        <label for="c9o"></label>
    </div>
</div>

</body>
</html>
