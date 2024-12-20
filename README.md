<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <style>
    body,
    html {
      height: 100%;
      width: 100%;
      margin: 0;
      display: flex;
      justify-content: center;
    }

    #left {
      width: 15%;
      height: 100%;
      background-color: rgb(255, 255, 255);
    }

    #right {
      width: 85%;
      height: 100%;
      background-color: rgb(239, 239, 239);
      overflow-y: auto;
      background-image: url(./我心里危险的东西/5CDAD07A47F03F6BA5B5FAF2A8B96F0E.gif);
    }

    .picture {
      text-align: center;
      background-image: url(./我心里危险的东西/F4A847987C2C79BE6CBEEC74A8A19EAF.gif);
    }

    img {
      height: 100px;
      width: 100px;
      margin: 25px auto 0;
      border-radius: 50%;
    }

    ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
    }

    li {
      height: 50px;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: rgba(175, 175, 175, 0.836);
    }

    li:hover {
      background-color: rgb(225, 225, 225);
    }

    a {
      text-decoration: none;
      color: rgb(234, 234, 234);
    }

    img:nth-child(2) {
      height: 300px;
      width: 300px;
      border-radius: 0;
      border: 2px solid rgb(193, 193, 193);
    }

    #character {
      display: flex;
      height: 350px;
      width: 100%;
      justify-content: space-around;
      background-color: rgba(202, 202, 202, 0.651);
      border-radius: 8px;
    }

    #character img {
      height: 200px;
      width: 200px;
      display: inline-block;
    }

    .po {
      text-align: center;
    }

    #right>div {
      margin: 0 80px;
      position: relative;
    }

    .xinxi {
      margin-top: 30px;
      display: inline-block;
      position: absolute;
      left: 450px;
    }

    span {
      font-size: 25px;
      font-weight: 700;
    }

    h2 {
      margin: 40px auto 20px;
    }

    .dynamic-box {
      display: none;
      overflow: auto;
    }

    .active {
      display: block;
    }

    .dynamic-item {
      margin-bottom: 20px;
      text-align: center;
      background-color: rgb(233, 233, 233);
      display: flex;
      justify-content: center;
      border: 2px solid rgb(188, 188, 188);
    }

    .dynamic-item:hover {
      box-shadow: 8px 8px 8px rgb(154, 154, 154);
    }

    .dynamic-item img {
      width: 300px;
      max-width: 500px;
      height: auto;
      border-radius: 0;
      margin: 0;
    }

    #ll {
      position: sticky;
      top: 0;
      height: 40px;
      background-color: rgb(233, 233, 233);
      border: 2px solid rgb(203, 203, 203);
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .oo {
      margin: 30px auto;
      font-size: 20px;
      border: 2px solid rgb(237, 237, 255);
      width: 300px;
      background-color: rgb(248, 248, 248);
      padding: 35px;
      font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    }


    #character img:hover {
      box-shadow: 5px 5px 8px rgb(129, 129, 129);
      height: 210px;
      width: 210px;
    }

    #like {
      display: none;
    }

    video {
      width: 80%;
      height: auto;
      border: 2px solid black;
    }

    @keyframes my {
      0% {
        opacity: 1;
      }

      100% {
        opacity: 0;
        display: none;
      }
    }

    .act {
      animation: my 1s forwards;
    }
  </style>
</head>

<body>
  <div id="left">
    <div class="picture">
      <img src="./我心里危险的东西/0F07F1F7870B539D67E02A0A72C03BEE.jpg" alt="图片">
      <p style="color: aliceblue;margin: 0;height: 35px;">山田 杏奈</p>
    </div>
    <ul>
      <li><a href="#" id="info-link">个人信息</a></li>
      <li><a href="#" id="likes-link">喜欢</a></li>
      <li><a href="#" id="dynamic-link">动态</a></li>
    </ul>
  </div>
  <div id="right">
    <div class="pp">
      <div id="info-box" class="active">
        <h1>个人信息</h1>
        <img src="./我心里危险的东西/0F07F1F7870B539D67E02A0A72C03BEE.jpg" alt="图片">
        <div class="xinxi">
          <p><span>姓名：</span>山田 杏奈</p>
          <p><span>性别：</span>女</p>
          <p><span>生日：</span>9月10日</p>
          <p><span>身高：</span>171.9cm</p>
          <p><span>体重：</span>55.5kg</p>
          <p><span>血型：</span>AB型</p>
        </div>
        <h2>人物关系</h2>
        <div id="character">
          <div class="po">
            <img src="./我心里危险的东西/D26523944BDCCBBD4BF3E1A203400AE1.jpg" alt="图片">
            <p><span>市川 京太郎</span></p>
            <p>男朋友</p>
          </div>
          <div class="po">
            <img src="./我心里危险的东西/F4096AAA7EEE47ED3581AF3AD68911EF.jpg" alt="图片">
            <p><span>小林 千寻</span></p>
            <p>好友</p>
          </div>
          <div class="po">
            <img src="./我心里危险的东西/7296886DA84DAD095E8D23A5B728AE0A.jpg" alt="图片">
            <p><span>半泽 由里子</span></p>
            <p>同学</p>
          </div>
          <div class="po">
            <img src="./我心里危险的东西/BD419A49E181B2BEB5FBE8D4E1D665C6.jpg" alt="图片">
            <p><span>安堂 环奈</span></p>
            <p>同学</p>
          </div>
        </div>
      </div>
    </div>

    <div id="dynamic-box" class="dynamic-box">
      <h1>动态</h1>
      <div id="ll">
        <input type="file" id="dynamic-upload">
        <input type="text" id="dynamic-description" placeholder="描述">
        <button onclick="addDynamic()">添加动态</button>
      </div>
      <div id="dynamic-list">
        <div class="dynamic-item">
          <img src="./我心里危险的东西/6F2FC1189CD1F438763C6A9E69C93A2D.jpg" alt="图片">
          <p class="oo">山田杏奈，樱井纪雄创作的漫画《我心里危险的东西》及其衍生作品中的登场的女主角。由羊宫妃那配音。
            山田杏奈是学校第一美少女，作为模特和演员也很活跃。性格上比较天真烂漫。</p>
          <button onclick="removeDynamic(this)">删除</button>
        </div>
        <div class="dynamic-item">
          <img src="./我心里危险的东西/DF7A2A995DFCFCFFAD531E50465954F3.jpg" alt="图片">
          <p class="oo">山田杏奈，樱井纪雄创作的漫画《我心里危险的东西》及其衍生作品中的登场的女主角。由羊宫妃那配音。
            山田杏奈是学校第一美少女，作为模特和演员也很活跃。性格上比较天真烂漫。</p>
          <button onclick="removeDynamic(this)">删除</button>
        </div>
        <div class="dynamic-item">
          <img src="./我心里危险的东西/DBCA0C8013CD2FEE22076170C53218C6.jpg" alt="图片">
          <p class="oo">山田杏奈，樱井纪雄创作的漫画《我心里危险的东西》及其衍生作品中的登场的女主角。由羊宫妃那配音。
            山田杏奈是学校第一美少女，作为模特和演员也很活跃。性格上比较天真烂漫。</p>
          <button onclick="removeDynamic(this)">删除</button>
        </div>
      </div>
    </div>

    <div id="like">
      <h1>我的喜欢</h1>
      <div style="width: 100%;text-align: center;">
        <video controls>
          <source src="./我心里危险的东西/3_prob4_x264.mp4">
        </video>
        <div style="width: 100%;text-align: center;">
          <video controls>
            <source src="./1.html+css/课/蕾娜改_x264.mp4">
          </video>
        </div>
      </div>
    </div>

    <script>
      const infoLink = document.getElementById('info-link');
      const dynamicLink = document.getElementById('dynamic-link');
      const like = document.getElementById('likes-link')
      const infoBox = document.getElementById('info-box');
      const dynamicBox = document.getElementById('dynamic-box');
      const pp = document.querySelector('.pp')
      const likebox = document.querySelector('#like')

      infoLink.addEventListener('click', function () {
        pp.style.display = 'block'
        dynamicBox.style.display = 'none'
        likebox.style.display = 'none'
      });

      like.addEventListener('click', function () {
        likebox.style.display = 'block'
        dynamicBox.style.display = 'none'
        pp.style.display = 'none'
      })
      dynamicLink.addEventListener('click', function () {
        pp.style.display = 'none'
        dynamicBox.style.display = 'block'
        likebox.style.display = 'none'
      });

      function addDynamic() {
        const fileInput = document.getElementById('dynamic-upload');
        const descriptionInput = document.getElementById('dynamic-description');
        const file = fileInput.files[0];
        const description = descriptionInput.value;

        if (file) {
          const reader = new FileReader();
          reader.onload = function (e) {
            const dynamicList = document.getElementById('dynamic-list');
            const div = document.createElement('div');
            div.className = 'dynamic-item';
            div.innerHTML = `<img src="${e.target.result}" alt="动态图片"><p class='oo'>${description}</p><button onclick="removeDynamic(this)">删除</button>`;
            dynamicList.appendChild(div);
          };
          reader.readAsDataURL(file);
        }
      }

      function removeDynamic(button) {
        const div = button.parentElement;
        div.remove();
      }
    </script>
</body>

</html>
