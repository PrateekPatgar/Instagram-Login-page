# Instagram-Login-page
Instagram login page using HTML  and CSS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <Style type="text/css" media="all">
        body{
            background-color: yellow;
        }
    </Style>
    <style>
       .div{
            width: 300px;
            height: 400px;
            top: 50%;
            left: 50%;
            position: absolute;
            margin-top: -200px;
            margin-left: -150px;
            background-color: bisque;
            border: 20px solid red;
            box-sizing: border-box;
       }
    </style>
</head>
<body>
    <div class="div">
       <div style="text-align: center;"><br><br><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Instagram_logo_2016.svg/2048px-Instagram_logo_2016.svg.png" width="80"></div>
       <br><br>
       <div style="text-align: center;">
           <form action="/action.php">
            <input type="text" placeholder="User Name">
            <br><br>
            <input type="password" placeholder="Password">
            <br><br>
            <!-- <select name="gender" id="1">
                <option value="male">Gender</option>
                <option value="male">Male</option>
                <option value="male">Female</option>
                <option value="male">Transe Gender</option>
            </select> -->
            <input type="checkbox">I'm not a robot
            <br><br>
            <input type="submit" value="Sign in">
            <input type="submit" value="Sign up ">
           </form>
       </div>
    </div>
</body>
</html>
