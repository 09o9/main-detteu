<template>
  
    <link rel="preconnect" href="https://fonts.googleapis.com"> <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2? family=Black+Han+Sans&family=Noto+Sans+KR:wght@900&display=swap" rel="stylesheet">
  
  <div id="app">
    <div class="image-container">
      <img src="./assets/Notes_240314_220634_1.jpg" alt="가로로 짧고 세로로 긴 이미지" class="centered-image">
      <div class="image-text">
      <h1 >Hello World</h1>
      <h2 >I'm Detteu</h2>
      <br> <br>
      
      <h2 id="st">STACK </h2>
      <div class="profile">
        <img src="./assets/html2.png" alt="프로필 이미지">
        <h3>HTML</h3>
    </div>
    <br>
    <div class="profile">
        <img src="./assets/css3.png" alt="프로필 이미지">
        <h3>CSS</h3>
    </div>
    <br>
    <div class="profile">
        <img src="./assets/js.png" alt="프로필 이미지">
        <h3>JAVASCRIPT</h3>
    </div>
    <br>
    <div class="profile">
        <img src="./assets/logo.png" alt="프로필 이미지">
        <h3>VUE.JS</h3>
    </div>
    <div class="dis">
      <h2>DSICORD</h2>
    <iframe src="https://discord.com/widget?id=1214398041792970783&theme=dark" width="350" height="300" allowtransparency="true" frameborder="0" sandbox="allow-popups allow-popups-to-escape-sandbox allow-same-origin allow-scripts"></iframe>
  </div>
    </div>
  </div>
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style>
#app {
  -webkit-user-select: none; /* Safari */
                -moz-user-select: none; /* Firefox */
                -ms-user-select: none; /* IE 10+ and Edge */
                user-select: none; /* Standard syntax */
                font-family: 'Black Han Sans', 산세리프;
                font-family: 'Noto Sans KR', 산세리프;
  border-radius: 30px;
  background: linear-gradient(to right, #ff4c4c, #1e56ce); /* 왼쪽에서 오른쪽으로 그라데이션 효과 */
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
 
}

.image-container {
 
  position: relative;
  display: flex; /* 내부 요소를 가운데 정렬하기 위해 Flexbox를 사용합니다. */
  justify-content: center; /* 수평 가운데 정렬합니다. */
 
}

.centered-image {
  pointer-events: none;
  margin-bottom: 50px;
  margin-top: 50px;
  border-radius: 50px;
  max-width: 100%; /* 이미지가 너무 커질 경우 컨테이너에 맞게 조정합니다. */
  max-height: 100%; /* 이미지가 너무 커질 경우 컨테이너에 맞게 조정합니다. */
}

.image-text {
 
  color: #ff0000;
  font-size: 30px;
  position: absolute; /* 이미지 컨테이너 내에 절대 위치로 설정합니다. */
  margin-top: 30px;
  padding: 10px 20px;
  border-radius: 5px;
}
.image-text h1, h2 {
  background: linear-gradient(to left, rgb(255, 0, 0), rgb(0, 4, 255));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}
#st {
 
  background: linear-gradient(to left, rgb(46, 129, 255), #9dff00);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  
}
.dis h2 {
  background: linear-gradient(to left, rgb(0, 102, 255), #9900ff);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}

.profile {
  color: #ffffff;
  padding: 15px 25px;
  border-radius: 30px;
  background-color: #2c3e50a6;
    display: flex;
    align-items: center;
}

.profile img {
  margin-left: 10px;
    width: 70px; /* 프로필 이미지의 너비 */
    height: auto; /* 프로필 이미지의 높이를 자동 조정하여 비율 유지 */
    border-radius: 25%; /* 원형 프로필 이미지를 만듭니다. */
    margin-right: 10px; /* 이미지와 텍스트 사이의 간격을 조정합니다. */
}

.profile h3 {
    font-size: 50px; /* 개발자 이름의 글꼴 크기를 조정합니다. */
    font-weight: bold; /* 개발자 이름의 글꼴 두껍게 설정 */
    margin: 0; /* 개발자 이름의 위쪽 및 아래쪽 여백을 제거합니다. */
}

</style>
