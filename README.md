# Spockdemo
test git repos
<br>
Planning to add exercise calculator 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday!</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="timer-container">
        <h1 id="countdown">5</h1>
    </div>
    <div id="message-container" style="display: none;">
        <h1 id="happy-birthday-text">Happy Birthday!</h1>
        <div id="animations"></div>
        <!-- Interactive Gift Box -->
        <div id="gift-box-container">
            <img id="gift-box" src="gift-box.png" alt="Gift Box">
            <span id="gift-box-text">Click here to unbox your gift</span>
        </div>
    </div>
    <div id="redeem-container" style="display: none;">
        <h1 id="redeem-text">Click to redeem</h1>
    </div>
    <div id="images-container" style="display: none;">
        <!-- Images to pop in -->
        <div class="image-item" id="food-img-container">
            <img id="food-img" class="pop-image" src="food.png" alt="Food">
            <p class="image-text">Unlimited fried chicken</p>
        </div>
        <div class="image-item" id="spa-img-container">
            <img id="spa-img" class="pop-image" src="spa.png" alt="Spa">
            <p class="image-text">Infinite relaxation</p>
        </div>
        <div class="image-item" id="travel-img-container">
            <img id="travel-img" class="pop-image" src="travel.png" alt="Travel">
            <p class="image-text">Unrestricted gateways</p>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
