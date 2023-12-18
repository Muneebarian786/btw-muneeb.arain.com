# btw-muneeb.arain.com
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" href="style.css">
.resized-image {
    width: 200px;
    height: 150px;
}
        body {
            background: url('https://source.unsplash.com/1920x1080/?nature,landscape') no-repeat center center fixed;
            background-size: cover;
            font-family: Arial, sans-serif;
            margin: 0;
        }

        header {
            color: black;
            padding: 50px;
            text-align: center;
        }

        nav {
            background: black;
            padding: 5px;
            text-align: center;
            position: fixed;
            
        }

        nav a {
            color:white;
            margin: 0 85px;
            text-decoration: none ;
        }

        .login-container {
            max-width: 600px;
            margin: 40px auto;
            padding: 30px;
            background: lightcyan;
            border-radius: 15px;
            border: soli black;
        }

        .login-wrapper {
            margin-bottom: 60px;
        }

        .input-box {
            margin-bottom: 30px;
        }

        .input-label {
            font-weight: bold;
            margin-bottom: 5px;
        }

        input {
            width: 90%;
            padding: 10px;
            box-sizing: border-box;
            margin-bottom: 10px;
        }

        .remember-me {
            display: flex;

        
        }

        .submit-btn {
            background: #333;
            color: #fff;
            padding: 10px 20px;
            border: none; 
            border-radius: 3px;
        }

        .info {
            margin-bottom: 30px;
        }

        .bottom {
            margin-top: 40px;
            margin: 0 100px;
            
            
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
            left: 0%;
        }
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        .about {
            background-color: #3498db;
            color: #fff;
            text-align: center;
            padding: 1em;
        }
        section {
            padding: 2em;
            text-align: center;
        }
        
        .learninghub { 
            text-align: center;
            background-color: #3498db;
            
            }
            
                    .signup-container {
                        max-width: 600px;
                        margin: 40px auto;
                        padding: 30px;
                        background: lightcyan;
                        border-radius: 15px;
                        border: solid black;
                    }
            
                    .signup-wrapper {
                        margin-bottom: 30px;
                    }
            
                    .input-box {
                        margin-bottom: 20px;
                    }
            
                    .input-label {
                        font-weight: bold;
                        margin-bottom: 5px;
                    }
            
                    input {
                        width: 90%;
                        padding: 10px;
                        box-sizing: border-box;
                        margin-bottom: 10px;
                    }
            
                    .submit-btn {
                        background: #333;
                        color: #fff;
                        padding: 10px 20px;
                        border: none; 
                        border-radius: 3px;
                    }
            
                    .info {
                        margin-bottom: 20px;
                    }
            
                    .bottom {
                        text-align: center;
                        margin-top: 30px;
                    }
                    .learninghub { 
                        text-align: center;
                        background-color: #3498db;
                        
                        }
                                .contact-container {
                                    max-width: 600px;
                                    margin: 40px auto;
                                    padding: 30px;
                                    background: lightcyan;
                                    border-radius: 15px;
                                    border: solid black;
                                }
                        
                                .social-icons {
                                    text-align: center;
                                    margin-bottom: 30px;
                                }
                        
                                .social-icons i {
                                    font-size: 0px;
                                    margin: 0 15px;
                                    color: #333;
                                }
                        
                                .info {
                                    margin-bottom: 20px;
                                }
                        
                                .bottom {
                                    text-align: center;
                                    margin-top: 30px;
                                }
                            
.textcolor {
color: red;

} 
   
</head>

<body>

<script>
    // Function to set a cookie
    function setCookie(name, value, days) {
        var expires = "";
        if (days) {
            var date = new Date();
            date.setTime(date.getTime() + (days * 24 * 60 * 60 * 1000));
            expires = "; expires=" + date.toUTCString();
        }
        document.cookie = name + "=" + value + expires + "; path=/";
    }

    // Function to get a cookie
    function getCookie(name) {
        var nameEQ = name + "=";
        var cookies = document.cookie.split(';');
        for (var i = 0; i < cookies.length; i++) {
            var cookie = cookies[i];
            while (cookie.charAt(0) === ' ') cookie = cookie.substring(1, cookie.length);
            if (cookie.indexOf(nameEQ) === 0) return cookie.substring(nameEQ.length, cookie.length);
        }
        return null;
    }

    // Function to delete a cookie
    function deleteCookie(name) {
        document.cookie = name + "=; expires=Thu, 01 Jan 1970 00:00:00 UTC; path=/;";
    }

    // Example usage
    setCookie("exampleCookie", "value123", 30); // Set a cookie named "exampleCookie" with value "value123" that expires in 30 days

    var cookieValue = getCookie("exampleCookie"); // Get the value of the "exampleCookie" cookie
    console.log("Cookie Value:", cookieValue);

    // Uncomment the line below to delete the "exampleCookie" cookie
    // deleteCookie("exampleCookie");
</script>



    <nav>
        <a href="E:\new project of html\web.html">Home</a>
        <a href="E:\new project of html\about.html">About</a>
        <a href="E:\new project of html\contact us.html">Contact</a>
        <a href="E:\new project of html\signup.html">Signup</a>
        <a href="#">courses</a>
        <a href="#">FAQs</a>

    </nav>
    <body style="background: url('https://source.unsplash.com/1920x1080/?nature,landscape') no-repeat center center fixed; background-size: cover;">
        <header>
            <h1 class="muneebweblogo"> learning Hub</h1>
            <img class="resized-image" src="https://dcassetcdn.com/design_img/134255/120336/120336_1804168_134255_image.jpg" alt="Muneeb Web Logo">
        </header>
    
       
    
        <div class="login-container">
            <h1 class="muneebweblogo">Sign in to Learning Hub</h1>
    
            <form>
                <div class="login-wrapper">
                    <div class="input-box">
                        <div class="input-label">Username or Email Address</div>
                        <input type="text" name="username" required>
                    </div>
    
                    <div class="input-box">
                        <div class="input-label">
                            <span>Password</span>
                            <a href="#" class="link">Forgot Password</a>
                        </div>
                        <input type="password" name="password" required>
                    </div>
    
                    <div class="input-box remember-me">
                        <div class="input-label">
                            <input type="checkbox" name="remember"> Remember Me
                        </div>
                    </div>
    
                    <button type="submit" class="submit-btn">Log in</button>
                </div>
            </form>
    
            <div class="info">
                <span>New to learning hub? <a href="E:\new project of html\signup.html" class="link">Create an account</a></span>
            </div>
    
            <p class="bottom">
                <a href="#">Terms</a>
                <a href="#" class="link">Privacy</a>
                <a href="#" class="link">Docs</a>
                <a href="#" class="link"> Contact Muneeb Web Support</a>
            </p>
        </div>
    
        <footer>
            &copy; 2023 learning us. All rights reserved.
        </footer>
    </body>
</body>
</html>
