<template>
    <div class="container">
        <div class="wrap">
            <h1>Sign in.</h1>
            <form action="">
                <button>Continue with Google</button>
                <button>Continue with Facebook</button>
                <p class="para-1">or</p>
                <input type="email" placeholder="Email" required/>
                <input type="password" placeholder="Password" required/>
                <input type="button" value="Sign In" />
            </form>
            <p class="para-1">
                Not have an account? <a href="signup.html"> <b> Create Account</b> </a>
            </p>
            <p class="para-2">
                <a href="signup.html"> <b>Forgot Password?</b> </a>
            </p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'CustomInput',
}
</script>

<style scoped>
    html, body, div, span, applet, object, iframe,h1, h2, h3, h4, h5, h6, p{
        margin: 0;
        padding: 0;
        border: 0;
        font-size: 100%;
    }

    ol, ul {
        list-style: none;
    }
    .container {        
        background-color: rgb(32, 30, 32);
        height: 100vh;
        align-items: center;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
    h1 {
        color: #fff;
    }
    form {
        max-width: 420px;
        padding: 10px;
        margin: auto;
        text-align: center;
    }
    input, button {
        width: 300px;
        color: #fff;
        font-family: Arial, Helvetica, sans-serif;
        padding: 10px ;
        box-sizing: border-box;
        border: 3px solid #444140;
        border-radius: 10px;
        font-size: 14px;
        background-color: rgb(32, 30, 32);
        margin-bottom: 15px;
    }
    input::placeholder {
        color: #ddd;
        opacity: 1;
    }
    input[type="button"] {
        background-color: #f08080;
        border: 0;
        padding:  15px 10px;
        border-radius: 10px;
        font-weight: bold;
        margin-top: 10px;
    }
    p {
        text-align: center;
        font-size: 15px;
        margin: 0;
    }
    .para-1 {
        text-align: center;
        color: #6d6a75;
        font-size: 15px;
        margin-bottom: 15px;
    }

    .para-1 a, .para-2 a {
        color: white;
        text-decoration: none;
    }

    .para-2 {
        color: white;
    }
</style>