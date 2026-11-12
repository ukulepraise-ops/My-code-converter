
<!DOCTYPE html>
<html>
<head>
    <title>My First Converter</title>

    <style>
        body {
            font-family: Arial;
            background: #eeeeee;
            text-align: center;
            padding: 20px;
        }

        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
        }

        textarea {
            width: 90%;
            height: 100px;
            padding: 10px;
        }

        button {
            background: green;
            color: white;
            padding: 12px;
            border: none;
            margin: 5px;
        }
    </style>
</head>

<body>

<div class="container">

    <h2>My First Text Converter</h2>

    <p>Enter your words below:</p>

    <textarea id="myText"></textarea>

    <br><br>

    <button onclick="convertUpper()">
        UPPERCASE
    </button>

    <button onclick="convertLower()">
        lowercase
    </button>

</div>

<script>
function convertUpper() {
    let text = document.getElementById("myText");
    text.value = text.value.toUpperCase();
}

function convertLower() {
    let text = document.getElementById("myText");
    text.value = text.value.toLowerCase();
}
</script>

</body>
</html>
