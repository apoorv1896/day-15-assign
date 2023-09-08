# day-15-assign
<div align="center">
  <img height="150" src="https://camo.githubusercontent.com/62da68eb62b1e5f175f7d1f0191dd89a653d7908feb22d37d4a0ab07365d6791/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f4d3967624264396e6244724f5475314d71782f67697068792e676966"  />
</div>

###

<div align="center">
  <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="linkedin logo"  />
  <img src="https://img.shields.io/static/v1?message=Youtube&logo=youtube&label=&color=FF0000&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="youtube logo"  />
  <img src="https://img.shields.io/static/v1?message=Twitter&logo=twitter&label=&color=1DA1F2&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="twitter logo"  />
</div>

###

<div align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=maurodesouza.maurodesouza&"  />
</div>

###

<h1 align="center">hey there 👋</h1>

###

<h3 align="left">👩‍💻  About Me</h3>

###

<p align="left">I'm ... from ....<br><br>- 🔭 I’m working as ...<br>- 📚 I'm currently learning ...<br>- ⚡ In my free time I ...</p>

###

<h3 align="left">🛠 Language and tools</h3>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" height="40" alt="go logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-plain.svg" height="40" alt="rust logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ruby/ruby-plain-wordmark.svg" height="40" alt="ruby logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dot-net/dot-net-plain-wordmark.svg" height="40" alt="dot-net logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain-wordmark.svg" height="40" alt="firebase logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original.svg" height="40" alt="amazonwebservices logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/circleci/circleci-plain.svg" height="40" alt="circleci logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" height="40" alt="kubernetes logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-plain-wordmark.svg" height="40" alt="docker logo"  />
</div>

###

<h3 align="left">🔥   My Stats :</h3>

###

<div align="center">
  <img src="https://streak-stats.demolab.com?user=maurodesouza&locale=en&mode=daily&theme=dark&hide_border=false&border_radius=5&order=3" height="220" alt="streak graph"  />
</div>

###

## i have created random pics generator using html css js
## Step 1 create html file
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animals picture Generator</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h3>Picture Generator</h1>
        <button class="btn" id="btn">Get pics</button>
        <div class="car-container">
            <!-- <img class="" src="https://c.files.bbci.co.uk/F382/production/_123883326_852a3a31-69d7-4849-81c7-8087bf630251.jpg"> -->
            <h3 class="">pixture</h3>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>

## Step 2 creating css file
body{
    margin: 0;
    display: flex;
    width: 100vw;
    height: 100vh;
    justify-content: center;
    background-color: aqua;
    align-items: center;
}

.container{
    background: rgb(171, 236, 21);
    border-radius: 10px;
    box-shadow: 0 10px 20px rgba(0,0,0,0.3);
    text-align: center;
    padding: 10px;
    width: 450px;
    margin: 5px;
}

.btn{
    background-color: rgb(128, 0, 115);
    color: aliceblue;
    padding: 10px 30px;
    font-size: 16px;
    margin-bottom: 30px;
    border-radius: 6px;
    cursor: pointer;

}

.btn:disabled{
    background-color: rgb(71, 105, 192);
    cursor: not-allowed;
}

.car-img{
    height: 300px;
    width: 300px;
    border-radius: 50%;
    border: 3px solid rgb(121, 139, 219);
}

.car-name{
    margin: 20px;
    background-color: rgb(243, 87, 123);
    color: aliceblue;
    padding: 10px;
    border-radius: 6px;
    font-size: 17px;
    font-weight: 600;
}

.car-container{
    display: none;
}

## step 3 similary creating js file and deploying html file on web browser
