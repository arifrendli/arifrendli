<html>
<head>
  <meta http-equiv="CONTENT-TYPE" content="text/html; charset=UTF-8">
  <title>profile photos</title>
</head>
<body>
  <div class="container">
  <div class="user-box">
  <img src="menu.png" class="menu">
    <img src="settings.png" class="settings">
  <img src="user.webp" class="user">
  <h3>I'm Frendli</h3>
  <p><strong>Halo semua saya Frendli salam kenal!!</strong></p>
  <div class="medsos">
  <img src="facebook.png" class="facebook">
    <a href="https://www.instagram.com/frendlii_?igsh=YzljYTk1ODg3Zg=="><img src="instagram.png" class="instagram"></a>
    <a href="https://vm.tiktok.com/ZS2JftFVB/"><img src="tiktok.png" class="tiktok"></a>
  </div>
    <button type="button">Follow Me</button>
    <div class="profile.bottom">
      <p><strong>Helloo! Im frendli you also can call me ari <br>
       Im just a boy who interested with motorcycle</strong></p>
    </div>
  </div>
  </div>
  <link rel="stylesheet" href="profile .css">
</body>
</html>

@import url(https://fonts.googleapis.com/css?family=Poppins)

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}

.container {
  width: 100%;
  height: 100%vh;
  background-image: url(background.jpg);
  background-size: cover;
  background-position: center;
  display: flex;
  align-items: center;
  justify-content: center;
}

.user-box {
  background: rgba(225, 225, 225, 0.2);
  text-align: center;
  padding: 70px 100px;
  color: white;
  position: relative;
  border-radius: 20px;
  box-shadow: 0 4px 30px rgba(0, 0, 0, 0);
  backdrop-filter: blur(5px);
  -webkit-backdrop-filter: blur(5px);
  border: 1px solid rgba(225, 225, 225, 0.2);
}

.menu {
  width: 25px;
  position: absolute;
  left: 40px;
  top: 40px;
}

.settings {
  width: 25px;
  position: absolute;
  right: 40px;
  top: 40px;
}

.user {
  width: 150px;
  border-radius: 50%;
  background-color: white;
  padding: 6px;
  margin-top: 40px;
}

.user-bottom {
  background: white;
  color: black;
  padding: 60px 0;
  margin-right: -100px;
  margin-left: -100px;
  margin-bottom: -70px;
  margin-top: 20px;
}

.user-box button {
  background: blue;
  color: white;
  border: none;
  cutline: none;
  box-shadow: 0 5px 10px rgba(244, 67, 54, 0.5);
  padding: 15px 60px;
  cursor: pointer;
  border-radius: 30px;
  margin-bottom: -50px;
  font-weight: 600px;
  font-size: 16px;
}

.user-box h3 {
  font-size: 30px;
  margin-top: 20px;
  font-weight: 600;
}

.medsos img {
  width: 30px;
  margin: 30px 5px;
  cursor: pointer;
}
