# chatbot
Projects/ChatBot/style.css
<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
    <meta charset="utf-8">
    <title>ChatGPT Clone</title>
    <link rel="stylesheet" href="style.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet"
        href="https://fonts.googleapis.com/css2?family=Material+Symbols+Rounded:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" />
    <script src="script.js" defer></script>
    <title>JS Chatbot | CodeJunkie</title>
    <link rel="stylesheet" href="style.css">
    <link rel="icon" type="image/x-icon" href="./favicon_io/favicon-32x32.png"> 
    <!--Google fonts link for icons-->
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" />
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Rounded:opsz,wght,FILL,GRAD@48,400,1,0" />
</head>

<body>
    <div class="chat-container"></div>
    <div class="typing-container">
        <div class="typing-content">
            <div class="typing-textarea">
                <textarea id="chat-input" spellcheck="false" placeholder="Enter a prompt here" required></textarea>
                <span id="send-btn" class="material-symbols-rounded">send</span>
            </div>
            <div class="typing-controls">
                <span id="theme-btn" class="material-symbols-rounded">light_mode</span>
                <span id="delete-btn" class="material-symbols-rounded">delete</span>
            </div>
<body class="show-chatbot">
    <button class="chatbot-toggler">
        <span class="material-symbols-outlined">mode_comment</span>
        <span class="material-symbols-outlined">close</span>
    </button>
    <div class="chatbot">
        <header>
            <h2>Chatbot</h2>
            <span class="close-btn material-symbols-outlined">close</span>
        </header>
        <ul class = "chatbox">
            <li class = "chat incoming">
                <span class="material-symbols-outlined">smart_toy</span>
                <p>Hi there 👋🏼 <br> How may I help you?</p>
            </li>
        </ul>
        <div class="chat-input">
            <textarea placeholder="Enter a meesage..." spellcheck="false" required></textarea>
            <span id = "send-btn" class="material-symbols-rounded">send</span>
        </div>

    </div>
    <script type="text/javascript" src="script.js"></script>
</body>

</html>
