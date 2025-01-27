<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>张梦婷我爱你</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(to bottom, #6a0dad, #483d8b);
            color: red;
            font-family: Arial, sans-serif;
            font-size: 2em;
            text-align: center;
        }
        .heart {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 100px;
            height: 100px;
            background: red;
            border-radius: 50px 50px 50px 50px / 50px 50px 0 0;
        }
        .heart::before {
            content: '';
            position: absolute;
            top: -50px;
            left: 25px;

