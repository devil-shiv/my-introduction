# my-introduction
my intro
<!DOCTYPE html>
<html>
    <head>
        <title>My Blog</title>
        <link href="https://fonts.googleapis.com/css?family=Handlee" rel="stylesheet">
        <!--Good Work-->
    </head>
   
    <body>
    <style>
html {
    margin: 0;
    padding: 0;
}
body {
    font-family: 'Handlee', cursive;
    font-size: 13pt;
    background-color: #efefef;
    padding: 10px;
    margin: 0;
}
h1 {
    font-size: 15pt;
    color: #20bcd5;
    text-align: center;
    padding: 18px 0 18px 0;
    margin: 0 0 10px 0;
}
h1 span {
    border: 4px dashed #20bcd5;
    padding: 10px;
}
p {
    padding: 0;
    margin: 0;
}
.img-circle {
    border: 3px solid white;
    border-radius: 50%;
}
.section {
    background-color: #fff;
    padding: 15px;
    margin-bottom: 10px;
    border-radius: 10px;
}
#header {
    background-image: url("https://www.sololearn.com/Uploads/header.jpg");
    background-size: cover;
}
#header img {
    display: block;
    width: 80px;
    height: 80px;
    margin: auto;
}
#header p {
    font-size: 25pt;
    color: #3b464c;
    padding-top: 5px;
    margin: 0;
    font-weight: bold;
    text-align: center;
}
.quote {
    font-size: 12pt;
    text-align: right;
    margin-top: 10px;
}
table {
    width: 100%;
}
table, th, td {
    border: 2px solid #cecece;
    border-collapse: collapse;
    text-align: center;
    table-layout: fixed;
}
.selected {
    background-color: #f36f48;
    font-weight: bold;
    color: white;
}
li {
    margin-bottom: 15px;
    font-weight: bold;
}
progress {
    width: 70%;
    height: 20px;
    color: #3fb6b2;
    background: #efefef;
}
progress::-webkit-progress-bar {
    background: #efefef;
}
progress::-webkit-progress-value {
    background: #3fb6b2;
}
progress::-moz-progress-bar {
    color: #3fb6b2;</
    background: #efefef;
}
iframe, audio {
    display: block;
    margin: 0 auto;
    border: 3px solid #3fb6b2;
}
hr {
    border: 0;
    height: 1px;
    background: #f36f48;
}
form {
    text-align: center;
    margin-top: 0;
}
.submit {
    background-color: #3fb6b2;
    padding: 12px 45px;
    border-radius: 5px;
    cursor: pointer;
    color: #ffffff;
    border: none;
    outline: none;
    margin: 0;
    font-weight: bold;
}
.submit:hover {
    background-color: #43a09d;
}
textarea {
    height: 100px;
}
input, textarea {
    margin-bottom: 10px;
    font-size: 11pt;
    padding: 15px 10px 10px;
    border: 1px solid #cecece;
    background-color: #efefef;
    color: #787575;
    border-radius: 5px;
    width: 70%;
    outline: none;
}
.face {
    transform: scale(0.4);
    margin: 0 auto;
    display: block;
    margin-top: -35px;
    margin-bottom: -25px;
}
#contacts img {
    height: 50px;
    width: 50px;
    margin-left: 7px;
    margin-right: 7px;
}
#contacts a {
    text-decoration: none;
}
#contacts img:hover {
    opacity: 0.8;
}
#contacts {
    text-align: center;
}
.copyright {
    font-size: 8pt;
    text-align: right;
    padding-bottom: 10px;
    color: grey;
}


</style>
        <!-- header start -->
        <div id="header" class="section">
            <img alt="" class="img-circle" src="https://code.sololearn.com/Icons/Avatars/0.jpg">
            <p>MOHIT AGARWAL</p>
        </div>
        <!-- header end -->
       
        <!-- About Me section start -->
        <div class="section">
            <h1><span>About Me</span></h1>
            <p>
                Hey! I'm <strong>MOHIT AGARWAL</strong>. Coding has changed my world. It's not just about apps. Learning to code gave me <i>problem-solving skills</i> and a way to communicate with others on a technical level. I can also develop websites and use my coding skills to get a better job.
                </p>
            <p class="quote">"written by MOHIT AGARWAL"</p>
        </div>
        <!-- About Me section end -->
       
        <!-- My Schedule section start -->
        <div class="section">
            <h1><span>My Coding Schedule</span></h1>
            <table>
                <tr>
                    <th>Day</th>
                    <th>Mon</th>
                    <th>Tue</th>
                    <th>Wed</th>
                    <th>Thu</th>
                    <th>Fri</th>
                </tr>
                <tr>
                    <td>8-8:30</td>
                    <td class="selected">Learn</td>
                    <td></td>
                    <td></td>
                    <td></td>
                    <td></td>
                </tr>
                <tr>
                    <td>9-10</td>
                    <td></td>
                    <td class="selected">Practice</td>
                    <td></td>
                    <td></td>
                    <td></td>
                </tr>
                <tr>
                    <td>1-1:30</td>
                    <td></td>
                    <td></td>
                    <td class="selected">Play</td>
                    <td></td>
                    <td></td>
                </tr>
                <tr>
                    <td>3:45-5</td>
                    <td></td>
                    <td></td>
                    <td></td>
                    <td class="selected">Code</td>
                    <td></td>
                </tr>
                <tr>
                    <td>6-6:15</td>
                    <td></td>
                    <td></td>
                    <td></td>
                    <td></td>
                    <td class="selected">Discuss</td>
                </tr>
            </table>
        </div>
        <!-- My Schedule section end -->
       
       
        <!-- My Skills section start -->
        <div class="section">
            <h1><span>My Skills</span></h1>
            <ul>
                <li>HTML <br />
                    <progress min="0" max="100" value="70"></progress>
                </li>
                <li>C++ <br />
                    <progress min="0" max="100" value="50"></progress>
                </li>
                <li>Python <br />
                    <progress min="0" max="100" value="20"></progress>
                </li>
                <li> c <br/>
                <progress min="0" max="100" value="40"></progress>
                </li>
            </ul>
        </div>
        <!-- My Skills section end -->
 
        <!-- Form section start -->
       <div class="section">
            <h1><span>Contact Me</span></h1>
           
            <svg class="face" height="100" width="100">
                <circle cx="50" cy="50" r="50" fill="#FDD835"/>
                <circle cx="30" cy="30" r="10" fill="#FFFFFF"/>
                <circle cx="70" cy="30" r="10" fill="#FFFFFF"/>
                <circle cx="30" cy="30" r="5" fill="#000000"/>
                <circle cx="70" cy="30" r="5" fill="#000000"/>
                <path d="M 30 70 q 20 20 40 0" stroke="#FFFFFF" stroke-width="5" fill="none" />
            </svg>
                
            <form>
                <input name="name" placeholder="Name" type="text" required /><br/>
                <input name="email" placeholder="Email" type="email" required /><br/>
                <textarea name="message" placeholder="Message" required ></textarea>
                <input type="submit" value="SEND" class="submit" />
            </form>
        </div>
        <!-- Form section end -->
       
        <!-- Contacts section start -->
        <div class="section" id="contacts">
            <h1><span>Follow Me</span></h1>
            <div>
                <a href="https://www.sololearn.com/" target="_blank">
                    <img alt="SoloLearn" src="https://www.sololearn.com/Uploads/icons/sololearn.png" />
                </a>
                <a href="#">
                    <img alt="Facebook" src="https://www.sololearn.com/Uploads/icons/facebook.png"/>
                </a>
                <a href="#">
                    <img alt="Twitter" src="https://www.sololearn.com/Uploads/icons/twitter.png" />
                </a>
            </div>
        </div>
        <!-- Contacts section end -->
       
        <div class="copyright">
            &copy; 2019 My Blog. All rights reserved.
        </div>
       
    </body>
</html>


