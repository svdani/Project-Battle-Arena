<template>
    <div class="container">
        <div class="input-group">
            <div class="bubble-box">Attack Name:</div>
            <input type="text" id="attackName">
        </div>
        <div class="middle-buttons">
            <button class="small-button"></button>
            <button class="small-button"></button>
            <button class="small-button"></button>
            <button class="small-button"></button>
        </div>
        <div class="input-group">
            <div class="bubble-box">Attack Damage:</div>
            <input type="text" id="attackDamage">
        </div>
        <button class="button">Create Attack</button>
    </div>
</template>

<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
    }
    .container {
        max-width: 600px;
        margin: 20px auto;
        padding: 20px;
        border: none;
        border-radius: 8px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }
    .input-group {
        margin-bottom: 15px;
    }
    .middle-buttons {
        display: flex;
        justify-content: space-between;
        margin-bottom: 15px;
    }
    .small-button {
        width: 50px;
        height: 50px;
        background-color: #ccc;
        border: none;
        border-radius: 5px;
        cursor: pointer;
    }
    .bubble-box {
        padding: 8px;
        background-color: #ccc;
        color: #333;
        border-radius: 5px;
        font-weight: bold;
        margin-right: 10px; /* Add space between the bubble and text */
        font-size: 14px; /* Adjust font size here */
    }
    .input-group label {
        display: block;
        margin-bottom: 5px;
    }
    .input-group input[type="text"] {
        width: calc(100% - 10px); /* Adjust width here */
        padding: 8px;
        border: none;
        border-radius: 5px;
        box-sizing: border-box;
        margin-top: 5px; /* Add space between bubble and input box */
    }
    .button {
        width: 100%;
        padding: 10px;
        background-color: #a3a28c;
        color: white;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        font-size: 16px;
        text-align: center;
        text-decoration: none;
    }
</style>
