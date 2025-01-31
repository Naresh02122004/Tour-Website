    /* Body Style */
    body {
        font-family: Arial, sans-serif;
        text-align: center;
        min-height: 100vh;
        background: linear-gradient(90deg, blue, red);
        color: white;
        padding-top: 60px;
    }

    /* Welcome Page */
    .welcome-container {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        height: 90vh;
    }

    h1 {
        font-size: 4rem;
        font-weight: bold;
        margin-bottom: 20px;
    }

    .image-label {
        font-size: 1.5rem;
        font-weight: bold;
        color: white;
    }

    /* Button */
    .button {
        margin-top: 20px;
        padding: 12px 24px;
        font-size: 1.2rem;
        font-weight: bold;
        color: white;
        background-color: rgba(0, 0, 0, 0.7);
        border: none;
        border-radius: 10px;
        cursor: pointer;
        transition: background 0.3s, transform 0.2s;
    }

    .button:hover {
        background-color: rgba(255, 255, 255, 0.3);
        transform: scale(1.1);
    }

    /* Second Page Content */
    .secondPage {
        display: none;
        width: 80%;
        margin: auto;
        text-align: left;
        margin-top: 40px;
        background-color: #f0f0f0;
        color: black;
    }

    h2 {
        margin-top: 20px;
    }

    ul {
        list-style-type: disc;
        margin-left: 20px;
    }

    /* Second Page Navigation - Top Right */
    .secondPage nav {
        position: fixed;
        top: 15px;
        right: 15px;
        text-align: right;
        background: rgba(0, 0, 0, 0.7);
        padding: 10px;
        border-radius: 5px;
    }

    .secondPage nav a {
        text-decoration: none;
        color: white;
        font-size: 1.2rem;
        margin: 0 15px;
        font-weight: bold;
    }

    .secondPage nav a:hover {
        color: yellow;
    }

    /* Places Section */
    .places-section {
        display: none;
        margin-top: 40px;
        background-color: #f4f4f4; /* Light gray background for places section */
        padding: 20px;
        color: black;
    }

    .place {
        margin-bottom: 30px;
        background: #fff;
        padding: 20px;
        border-radius: 10px;
        color: black;
    }

    .place img {
        max-width: 100%;
        height: auto;
        border-radius: 5px;
    }

    /* About Section */
    .about-section {
        display: block;
    }

    /* Login Section */
    .login-section {
        display: none;
        background-color: white;
        color: black;
        padding: 20px;
        border-radius: 10px;
        width: 100%;
        max-width: 400px;
        margin: 0 auto;
        text-align: left;
    }

    .login-section h2 {
        margin-bottom: 20px;
    }

    .login-section input {
        width: 100%;
        padding: 12px;
        margin-bottom: 15px;
        border-radius: 5px;
        border: 1px solid #ccc;
        font-size: 1rem;
    }

    .login-section button {
        width: 100%;
        padding: 12px;
        background-color: blue;
        color: white;
        border: none;
        border-radius: 5px;
        font-size: 1.2rem;
        cursor: pointer;
        margin-bottom: 10px;
    }

    .login-section button:hover {
        background-color: darkblue;
    }

    .login-section .google-signin {
        width: 100%;
        padding: 12px;
        background-color: #db4437;
        color: white;
        border: none;
        border-radius: 5px;
        font-size: 1.2rem;
        cursor: pointer;
        margin-bottom: 10px;
    }

    .login-section .google-signin:hover {
        background-color: darkred;
    }

    .login-section .signup {
        text-align: center;
    }

    .login-section .signup a {
        text-decoration: none;
        color: blue;
        font-size: 1.1rem;
    }

    .login-section .signup a:hover {
        text-decoration: underline;
    }

</style>
