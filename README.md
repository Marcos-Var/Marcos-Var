<style>
        .conte{
            display: flex;
            justify-content: space-evenly;
        }
        .atom-spinner, .atom-spinner * {
            box-sizing: border-box;
          }
      
          .atom-spinner {
            margin: 20px;
            height: 60px;
            width: 60px;
            overflow: hidden;
          }
      
          .atom-spinner .spinner-inner {
            position: relative;
            display: block;
            height: 100%;
            width: 100%;
          }
      
          .atom-spinner .spinner-circle {
            display: block;
            position: absolute;
            color: #ff1d5e;
            font-size: calc(60px * 0.24);
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
          }
      
          .atom-spinner .spinner-line {
            position: absolute;
            width: 100%;
            height: 100%;
            border-radius: 50%;
            animation-duration: 1s;
            border-left-width: calc(60px / 25);
            border-top-width: calc(60px / 25);
            border-left-color: #ff1d5e;
            border-left-style: solid;
            border-top-style: solid;
            border-top-color: transparent;
          }
      
          .atom-spinner .spinner-line:nth-child(1) {
            animation: atom-spinner-animation-1 1s linear infinite;
            transform: rotateZ(120deg) rotateX(66deg) rotateZ(0deg);
          }
      
          .atom-spinner .spinner-line:nth-child(2) {
            animation: atom-spinner-animation-2 1s linear infinite;
            transform: rotateZ(240deg) rotateX(66deg) rotateZ(0deg);
          }
      
          .atom-spinner .spinner-line:nth-child(3) {
            animation: atom-spinner-animation-3 1s linear infinite;
            transform: rotateZ(360deg) rotateX(66deg) rotateZ(0deg);
          }
      
          @keyframes atom-spinner-animation-1 {
            100% {
              transform: rotateZ(120deg) rotateX(66deg) rotateZ(360deg);
            }
          }
      
          @keyframes atom-spinner-animation-2 {
            100% {
              transform: rotateZ(240deg) rotateX(66deg) rotateZ(360deg);
            }
          }
      
          @keyframes atom-spinner-animation-3 {
            100% {
              transform: rotateZ(360deg) rotateX(66deg) rotateZ(360deg);
            }
          }
</style>
<div class="conte"> 
    <div class="atom-spinner">
      <div class="spinner-inner">
        <div class="spinner-line"></div>
        <div class="spinner-line"></div>
        <div class="spinner-line"></div>
        <!--Chrome renders little circles malformed :(-->
        <div class="spinner-circle">
          &#9679;
        </div>
      </div>
    </div>
  <h1 align="center">Hi everyone, I'm Marcos Vargas Azero (MVA)👋</h1>
</div>

<h3 align="center">💻 Systems engineer and martial artist 🥋</h3>

<hr/>

- 📚 Web developer and artiical intelligence
- 💪 Soon I will know the world of cybersecurity

<hr/>

<div align="center">
  
  <summary><b>:📈 &nbsp;GitHub Statistics</b></summary>
    <p align="center">
       <img height="143px" src="https://github-readme-stats.vercel.app/api?username=Marcos-Var&show_icons=true&include_all_commits=true&count_private=true&theme=react&hide_border=true&bg_color=0D1117&title_color=2AC900&icon_color=CF0900" />         
       <img height="140px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Marcos-Var&langs_count=10&layout=compact&theme=react&hide_border=true&bg_color=0D1117&title_color=2AC900&icon_color=CF0900" />
    </p>
  
<hr/>

<div align="center">
