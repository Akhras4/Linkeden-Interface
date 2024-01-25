<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Linkedin</title>
    <style >
        * {
    padding: 0px;
    margin: 0px;
    box-sizing: border-box;
}

.head {
    width: 100%;
    height: 20%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px;
}

.nav {
    display: flex;
}

.nav a {
    padding: 5px;
    border-right: 1px solid black;
    text-decoration: none;
    color: lightskyblue;
}

.main-con {
    background-color: rgb(230, 230, 230);
    width: 100%;
    height: 460px;
    border-top: 5px solid lightblue;
}

.con-body {
    margin: 30px;
    background: white;
    display: flex;
    flex-direction: column;
   
}

.con-top {
    display: flex;
    flex-direction: row;
}

.con-left {
    width: 60%;
    height: 75%;
    margin-top: 20px;
    margin-left: 20px;
}

h3 {
    color: lightskyblue;
}

.con-left-content {
    display: grid;
    grid-template-areas: "a a"
        "a a"
        "a a";
    justify-content: start;
    align-items: center;
}

.con-right {
    width: 30%;
    border: 1px solid lightgray;
    border-radius: 5px;
    margin: 20px;
}

.join {
    background-color: lightskyblue;
    padding-left: 10px;
    padding-top: 5px;
    height: 10%;
    font-weight: bold;
    
}

.con-login {
    display: grid;
    grid-template-areas: "a a"
        "a a"
        "a a"
        "a a"
        "a a";
    justify-content: space-around;
    align-items: center;
    gap: 10px;
    margin: 10px;
}

.con-right label {
    font-weight: bold;
}

.con-right input {
    font-weight: bold;
}

.submit {
    background-color: lightgreen;
    width: 50%;
}

.con-bott {
    margin-top: 20px;
}

.con-bott-1 {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 10px;
    margin-bottom: 10px;
    width: 100%;
}

.con-bott-1 label {
    font-size: 20px;
    font-weight: bold;
}

.con-bott-1 p {
    font-size: 20px;
    font-weight: bold;
}

.con-bott-1 a {
    padding-left: 6px;
    text-decoration: none;
    color: lightskyblue;
}

.GO {
    width: 30px;
    height: 30px;
}

.con-bott-1 p {
    font-size: 15px;
    color: rgb(180, 180, 180);
}
hr{
    margin: 0px 40px 0px 40px;
}
.con-footer {
    border-top: 3px solid rgb(204, 204, 204);
    background-color: rgb(247, 247, 247);
    width: 100%;
}

.con-bott-2 {
    display: flex;
    align-items: center;
    flex-direction: row;
    flex-wrap: nowrap;
}

.con-body-footer {
    margin: 20px 30px 20px 30px;
}

.con-bott-2 a {
    padding: 5px;
    border-right: 0.2px solid black;
    text-decoration: none;
    color: lightskyblue;
}

.con-bott-2 p {
    margin-right: 10px;
}

.con-bott-2 #link-term {
    border: none;
}

.con-bott-2 #user-agree {
    border-left: 0.2px solid black;
}

@media only screen and (max-width: 874px) {
    .con-top {
        display: flex;
        flex-direction: column;
    }

    .main-con {
        height: fit-content;

    }

    .con-right {
        width: fit-content;
    }

    .con-bott-1 {
        flex-wrap: wrap;
    }

    .con-bott-2 {
        flex-wrap: wrap;
    }
}
    </style>
</head>

<body>
    <header class="head">
        <div class="logo"><img src="logo1.png" alt="logo" width="175px" height="50px"></div>
        <nav class="nav">
            <a href="#">Home</a>
            <a href="#">What is Linkedin?</a>
            <a href="#">Join Today</a>
            <a href="#">Sign in</a>
        </nav>
    </header>
    <main class="main-con">
        <div class="con-body">
            <div class="con-top">
                <div class="con-left">
                    <h3>Over 24 milion professionals use Linkedin to<br>exchange informaton, ideas and oppotunities</h3>
                    <div class="con-left-content">
                        <img src="users.png" alt="">
                        <p>Stay informed about youe contacts and industry</p>
                        <img src="chats.png" alt="">
                        <p>Find the people & knowlede you need to achieve your goals</p>
                        <img src="bag.png" alt="">
                        <p>control your professional identity online</p>
                    </div>
                </div>
                <div class="con-right">
                    <p class="join">Join Linkedin Today</p>
                    <form action="">
                        <div class="con-login">
                            <label for=""> First Name</label>
                            <input type="text" min="1" max="1" required>
                            <label for="">Last Name</label>
                            <input type="text" min="1" max="1" required>
                            <label for="">Email</label>
                            <input type="email" required>
                            <div></div>
                            <input class="submit" type="submit" value="Continue">
                            <div></div>
                            <p class="a1">Already on Linkdin?<a href="/signin">Sign in</a></p>
                        </div>
                    </form>
                </div>
            </div>
            <hr>
            <div class="con-bott">
                <form action="">
                    <div class="con-bott-1">
                        <label for=""> Search for someone by name
                            <input type="text" min="1" max="1" required placeholder="First Name">
                            <input type="text" min="1" max="1" required placeholder="Last Name">
                            <input class="GO" type="submit" value="GO">
                        </label>
                    </div>
                </form>
                <div class="con-bott-1">
                    <p>Pepole directory:</p><a href="">A</a><a href="">B</a><a href="">C</a><a href="">D</a><a
                        href="">E</a><a href="">F</a><a href="">G</a><a href="">H</a><a href="">I</a><a href="">J</a><a
                        href="">K</a><a href="">L</a><a href="">M</a><a href="">N</a><a href="">O</a><a href="">P</a><a
                        href="">Q</a><a href="">R</a><a href="">S</a><a href="">U</a><a href="">V</a><a href="">W</a><a
                        href="">X</a><a href="">Z</a><a href="">more</a>
                </div>
            </div>
        </div>
    </main>
    <footer class="con-footer">
        <div class="con-body-footer">
            <div class="con-bott-2">
                <p>Company</p>
                <a href="">Customer Service</a><a href="">About Linkedin</a><a href="">Team</a><a href="">Blok</a><a
                    href="">Store</a><a href="">Advertise Withe Us</a><a href="">Work
                    With Us</a>

            </div>
            <div class="con-bott-2">
                <p>Tools</p>
                <a href="">Overview</a><a href="">Outlook Toolbar</a><a href="">JobsInsider</a><a href="">Widget</a>

            </div>
            <div class="con-bott-2">
                <p>Products</p>
                <a href="">Linkedin Answers</a><a href="">Linkedin Jobs</a><a href="">Linkedin
                    Updates</a>

            </div>
            <div class="con-bott-2">
                <p>Linkedin Corporation 2008</p> <a id="user-agree" href="">User Agreement</a><a href="">Privacy
                    Policy</a><a href="">Copyright
                    Policy</a>
            </div>
            <div class="con-bott-2">
                <p>Use of this site is subject to express<a id="link-term" href="">tems of use</a>, whic commerical use
                    of this
                    site.Byconfinuing past this page, you agree to abide by these terms.</p>
            </div>
        </div>
    </footer>
</body>

</html>

