
<!DOCTYPE html>
<html>
<head>
 <title> Sign-in form </title>
 <meta name="viewport" content=" width=device-width,initial-scale=1">
 <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">
 <style>
  *{
    box-sizing: border-box;

  }
  body
  {
    background: url('pic.jpeg');
    background-size: cover;
  }
  .wrap
  {
    max-width: 400px;
    margin: auto;
    margin-top: 50px;
    padding: 20px;
    font-family: sans-serif;
    background: #fff;
    border-radius: 10px;

  }
  .wrap hr{
    font-size: 2em;
    text-align: center;
  }
  button{
    padding: 10px;
    width: 49%;
    box-sizing: border-box;
    border:none;
    font-size: 1.3em;
    border-radius:10px;
    font-weight: bold;
  }
  button a{
       text-decoration:none;
       color: #fff;
  }
  button:nth-child(1)
  {
    background:grey;

  }
   button:nth-child(2)
  {
    background:grey;

  }
  button:hover{
    background: rgba(0,0,0,6);
  }
  .fa
  {
    font-size: 1.3em;
    font-weight: bold;
  }
  form
  {
    margin-top: 30px;

  }
  input[type=text],input[type=password],input[type=submit]{
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    font-size: 17px;
    border-radius: 5px;
    outline: none;
    border:none;
    border: 2px solid gray;
  }
  label{
    font-size:  20px;
    font-weight: bold;

  }
 </style>
</head>
<div class="wrap">
  <h2>Login in with</h2>
  <div class= "social media">
     <button><a href='https://www.facebook.com/'><i class ="fa fa-facebook"></i>Facebook</a> </button>
     <button><a href='https://accounts.google.com/ServiceLogin/identifier?elo=1&flowName=GlifWebSignIn&flowEntry=AddSession'><i class ="fa fa-Google"></i>Google</a> </button>
  </div>
     <form>
        <label>username</label><br>
        <input type="text">
        <label>password:</label><br>
        <input type="password" name="">
        <input type="submit" value="login"> 
    </form>
  <p>not a member?<a href='#'>sign up now</a></p>
</div>
</body>
</html>
