<!DOCTYPE html>
<html lang="en">
<head> <meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta charset="UTF-8">
<title>For You 💌</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #FFB6C1;
    overflow: hidden;
}

/* Background hearts */
body::before {
    content: "💗 💕 💖 💘 💝 💓 💞 💗 💕 💖💕💖💓💞💝💘💗💞💓💝💘💕💖💓💝💘💞💕💖💓💝💗💘💗💞💕💖💓💝💘💕💖💞💓💝💘💗💕💖💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💕💖💞💓💝💘💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💝💓💞💖💕💗💘💓💞💖💕💓💘💗💝💞💖💕💓💘💞💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓💘💗💝💞💖💕💓�💘💗💞💖💕💓💘💗💖💞💝";
    position: absolute;
    width: 110%;
    height: 30%;
    font-size: 35px;
    opacity: 0.3;
    animation: float 90s linear infinite;
}

@keyframes float {
    from { transform: translateY(0); }
    to { transform: translateY(-1000px); }
}

/* Card */
.container {
    position: absolute;
    top: 45%;
    left: 50%;
    transform: translate(-50%, -50%);
}

.card {
    background: white;
    padding: 25px;
    border-radius: 15px;
    width: 300px;
    text-align: center;
    box-shadow: 0 10px 30px rgba(0,0,0,0.2);
}

/* Input */
input {
    width: 90%;
    padding: 10px;
    border-radius: 20px;
    border: 1px solid #ff6b81;
    outline: none;
    text-align: center;
}

/* Button */
button {
    margin-top: 10px;
    padding: 10px;
    width: 95%;
    border: none;
    border-radius: 20px;
    background: #ff4d6d;
    color: white;
    font-weight: bold;
    cursor: pointer;
}

/* Message */
.message {
    margin-top: 15px;
    text-align: left;
    font-size: 14px;
    white-space: pre-line;
}

/* Hidden */
.hidden {
    display: none;
}
</style>
</head>

<body>

<div class="container">
    <div class="card">
        <h3>Enter Your Name 😊</h3>

        <input type="text" id="nameInput" placeholder="Your name here...">
        <button onclick="start()">Submit</button>

        <div class="message hidden" id="message"></div>
    </div>
</div>

<script>
function start() {
    let name = document.getElementById("nameInput").value;

    if (name.trim() === "") {
        alert("Enter your name muna (^-^)");
        return;
    }

    let msg = `Hi ${name}... (^^)♡

  I made this for you because I want to
make bawi sa lahat ng efforts na ginagawa mo for me.
I really appreciate everything you do.
gusto ko rin na ma-feel mo yung 
    same effort and care na binibigay mo sakin.
All your efforts always make me smile.
thankyou for always being there for me
kahit na ang gulo ko and hindi mo nako maintindihan minsan,
still nandyan kapa din, thankyou always🤗 `;
    
    
    let messageBox = document.getElementById("message");
    messageBox.classList.remove("hidden");

    typeEffect(msg, messageBox, 50);
}

function typeEffect(text, element, speed) {
    let i = 0;
    element.innerHTML = "";

    function typing() {
        if (i < text.length) {
            element.innerHTML += text.charAt(i);
            i++;
            setTimeout(typing, speed);
        }
    }

    typing();
}
</script>

</body>
</html>
