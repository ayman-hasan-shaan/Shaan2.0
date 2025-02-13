<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exclusive Login System</title>
    <!-- Google Fonts & Icons -->
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap">
    <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif; }
        body {   
            display: flex;   
            justify-content: center;   
            align-items: center;   
            height: 100vh;   
            background: linear-gradient(135deg, #1a2a6c, #b21f1f, #fdbb2d);   
        }
        .container {   
            width: 380px;   
            background: white;   
            border-radius: 10px;   
            box-shadow: 0px 5px 20px rgba(0, 0, 0, 0.2);   
            padding: 20px;   
            text-align: center;   
        }
        .profile-img {   
            width: 100px;   
            height: 100px;   
            border-radius: 50%;   
            border: 3px solid #ff6600;   
            box-shadow: 0px 0px 15px #ff6600;   
            margin: 10px auto;   
        }
        h2 { font-size: 22px; margin-bottom: 15px; }

        .input-box {  
            width: 100%;  
            margin-bottom: 15px;  
            position: relative;  
        }
        .input-box input {  
            width: 100%;  
            padding: 12px 45px;  
            border: 1px solid #ccc;  
            border-radius: 5px;  
            outline: none;  
            transition: 0.3s;  
        }
        .input-box input:focus { border-color: #ff6600; }
        .input-box .material-icons {  
            position: absolute;  
            left: 15px;  
            top: 50%;  
            transform: translateY(-50%);  
            font-size: 20px;  
            color: #ff6600;  
        }

        .btn {  
            width: 100%;  
            background: #ff6600;  
            color: white;  
            padding: 12px;  
            border: none;  
            border-radius: 5px;  
            cursor: pointer;  
            transition: 0.3s;  
            font-size: 16px;  
            font-weight: bold;  
        }
        .btn:hover { background: #cc5500; transform: scale(1.05); }

        /* Loader Animation - Heart */
        .loader {
            display: none;
            font-size: 50px;
            color: #ff6600;
            animation: heart-pulse 1.5s infinite;
        }
        @keyframes heart-pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.3); }
            100% { transform: scale(1); }
        }

        /* Loading Bar */
        .loading-bar {
            width: 100%;
            height: 5px;
            background-color: #ccc;
            margin-top: 15px;
            border-radius: 5px;
            overflow: hidden;
        }
        .progress {
            height: 100%;
            width: 0%;
            background-color: #ff6600;
            animation: fillBar 8s forwards;
        }
        @keyframes fillBar {
            0% { width: 0%; }
            100% { width: 100%; }
        }

        .social-section { display: none; text-align: center; }
        .social-section h3 { font-size: 18px; margin-top: 20px; color: #222; }
        
        /* Added text above social icons */
        .contact-text {
            font-size: 16px;
            font-weight: bold;
            margin-top: 30px;
            color: #333;
        }

        .social-icons {  
            margin-top: 15px;  
            display: flex;  
            justify-content: center;  
            gap: 15px;  
        }
        .social-icons a {  
            text-decoration: none;  
            font-size: 30px;  
            color: #333;  
            transition: 0.3s;  
            display: flex;  
            flex-direction: column;  
            align-items: center;  
        }
        .social-icons a:hover { color: #ff6600; }
        .social-icons span { font-size: 19px; margin-top: 8px; }

        .status {
            font-size: 20px;
            font-weight: bold;
            margin-top: 20px;
            color: #ff6600;
            animation: glow 1s infinite alternate;
        }
        @keyframes glow {
            0% { text-shadow: 0 0 10px #ff6600; }
            100% { text-shadow: 0 0 20px #ff0000; }
        }

        /* Footer Text */
        .footer-text {
            margin-top: 20px;
            font-size: 14px;
            color: #444;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="https://assets.onecompiler.app/42weepxyg/438xkk4z6/1737536160961.jpg" class="profile-img" alt="Profile">
        
        <!-- Signup Form -->
        <div class="form-box" id="signup-box">
            <h2>SHAAN 2.0</h2>
            <div class="input-box">
                <span class="material-icons">person</span>
                <input type="text" id="signup-username" placeholder="Username">
            </div>
            <div class="input-box">
                <span class="material-icons">lock</span>
                <input type="password" id="signup-password" placeholder="Password">
            </div>
            <button class="btn" onclick="signup()">Sign Up</button>
        </div>

        <!-- Login Form -->
        <div class="form-box" id="login-box" style="display: none;">
            <h2>Login</h2>
            <div class="input-box">
                <span class="material-icons">person</span>
                <input type="text" id="login-username" placeholder="Username">
            </div>
            <div class="input-box">
                <span class="material-icons">lock</span>
                <input type="password" id="login-password" placeholder="Password">
            </div>
            <button class="btn" onclick="login()">Login</button>
            <div class="loader" id="login-loader">&#10084;</div>
        </div>

        <!-- Loading Bar -->
        <div class="loading-bar" id="loading-bar" style="display: none;">
            <div class="progress"></div>
        </div>

        <!-- Social Icons Section -->
        <div class="social-section" id="social-section">
            <h3>Welcome, <span id="welcome-user"></span></h3>

            <!-- New Text -->
            <p class="contact-text">Click on the options below to contact me</p>

            <div class="social-icons">
                <a href="https://www.facebook.com/ayman.hasan.shaan" target="_blank"><span class="material-icons">facebook</span><span>Facebook</span></a>
                <a href="https://wa.me/message/7GF4LPFCNB4AE1" target="_blank"><span class="material-icons">chat</span><span>WhatsApp</span></a>
                <a href="https://tiktok.com/@shanthejoker" target="_blank"><span class="material-icons">music_note</span><span>TikTok</span></a>
                <a href="https://www.instagram.com/ayman_hasan_shaan_07?igsh=MWk0bnBsZXcwb2IxeQ==" target="_blank"><span class="material-icons">camera_alt</span><span>Instagram</span></a>
            </div>

            <div class="status">Relationship Status - Single</div>

            <!-- Footer Text -->
            <p class="footer-text">X-SHAAN - DEVELOPER - GFX ARTIST - ENTREPRENEUR</p>
        </div>
    </div>

    <script>
        function signup() {
    const username = document.getElementById("signup-username").value;
    const password = document.getElementById("signup-password").value;

    if (username === "" || password === "") {
        alert("Both fields are required!");
        return;
    }

    localStorage.setItem("username", username);
    localStorage.setItem("password", password);
    alert("Signup successful! Now login.");
    document.getElementById("signup-box").style.display = "none";
    document.getElementById("login-box").style.display = "block";
}

function login() {
    const username = document.getElementById("login-username").value;
    const password = document.getElementById("login-password").value;

    if (username === "" || password === "") {
        alert("Both fields are required!");
        return;
    }

    if (localStorage.getItem("username") === username && localStorage.getItem("password") === password) {
        document.getElementById("login-loader").style.display = "block";
        setTimeout(() => {
            document.getElementById("login-loader").style.display = "none";
            document.getElementById("login-box").style.display = "none";
            document.getElementById("loading-bar").style.display = "block";
            setTimeout(() => {
                document.getElementById("loading-bar").style.display = "none";
                document.getElementById("social-section").style.display = "block";
                document.getElementById("welcome-user").innerText = username;
            }, 2000);
        }, 1000);
    } else {
        alert("Invalid username or password");
    }
}
        
    </script>
</body>
</html>
