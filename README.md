- 👋 Hi, I’m @Zan6719
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Zan6719/Zan6719 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Synthwave Piano</title>
    <style>
        body {
            background: linear-gradient(135deg, #2b0055, #1a002d);
            color: #fff;
            font-family: 'Arial', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .piano {
            display: flex;
            position: relative;
            width: 90%;
            max-width: 600px;
            height: 200px;
            border: 2px solid #ff0080;
            border-radius: 10px;
            overflow: hidden;
        }
        .key {
            flex: 1;
            position: relative;
            border-left: 1px solid #ff0080;
            cursor: pointer;
            transition: background 0.2s;
        }
        .key:last-child {
            border-right: 1px solid #ff0080;
        }
        .white {
            background: #fff;
            height: 100%;
        }
        .black {
            background: #333;
            height: 60%;
            position: absolute;
            left: 75%;
            margin-left: -0.5em;
            width: 30%;
            z-index: 1;
        }
        .black:nth-child(2),
        .black:nth-child(4),
        .black:nth-child(7),
        .black:nth-child(9),
        .black:nth-child(11) {
            left: 75%;
        }
        .black:hover, .white:hover {
            background: #ff0080;
        }
    </style>
</head>
<body>
    <div class="piano">
        <div class="key white" data-note="C"></div>
        <div class="key black" data-note="C#"></div>
        <div class="key white" data-note="D"></div>
        <div class="key black" data-note="D#"></div>
        <div class="key white" data-note="E"></div>
        <div class="key white" data-note="F"></div>
        <div class="key black" data-note="F#"></div>
        <div class="key white" data-note="G"></div>
        <div class="key black" data-note="G#"></div>
        <div class="key white" data-note="A"></div>
        <div class="key black" data-note="A#"></div>
        <div class="key white" data-note="B"></div>
        <div class="key white" data-note="C2"></div>
    </div>

    <script>
        const keys = document.querySelectorAll('.key');
        const audioContext = new (window.AudioContext || window.webkitAudioContext)();

        keys.for
        <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Synthwave Piano</title>
    <style>
        body {
            background: linear-gradient(135deg, #2b0055, #1a002d);
            color: #fff;
            font-family: 'Arial', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .piano {
            display: flex;
            position: relative;
            width: 90%;
            max-width: 600px;
            height: 200px;
            border: 2px solid #ff0080;
            border-radius: 10px;
            overflow: hidden;
        }
        .key {
            flex: 1;
            position: relative;
            border-left: 1px solid #ff0080;
            cursor: pointer;
            transition: background 0.2s;
        }
        .key:last-child {
            border-right: 1px solid #ff0080;
        }
        .white {
            background: #fff;
            height: 100%;
        }
        .black {
            background: #333;
            height: 60%;
            position: absolute;
            left: 75%;
            margin-left: -0.5em;
            width: 30%;
            z-index: 1;
        }
        .black:nth-child(2),
        .black:nth-child(4),
        .black:nth-child(7),
        .black:nth-child(9),
        .black:nth-child(11) {
            left: 75%;
        }
        .black:hover, .white:hover {
            background: #ff0080;
        }
    </style>
</head>
<body>
    <div class="piano">
        <div class="key white" data-note="C"></div>
        <div class="key black" data-note="C#"></div>
        <div class="key white" data-note="D"></div>
        <div class="key black" data-note="D#"></div>
        <div class="key white" data-note="E"></div>
        <div class="key white" data-note="F"></div>
        <div class="key black" data-note="F#"></div>
        <div class="key white" data-note="G"></div>
        <div class="key black" data-note="G#"></div>
        <div class="key white" data-note="A"></div>
        <div class="key black" data-note="A#"></div>
        <div class="key white" data-note="B"></div>
        <div class="key white" data-note="C2"></div>
    </div>

    <script>
        const keys = document.querySelectorAll('.key');
        const audioContext = new (window.AudioContext || window.webkitAudioContext)();

        keys.for
        
