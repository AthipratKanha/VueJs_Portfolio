<template>
    <div>
        <h1 class="content-title"><font-awesome-icon icon="hammer" class="icon"/> Works</h1>
        
        <ul class="works">
          <li class="card">
            <img class="card-img" src="../assets/work/colmar.png" alt="">
            <div class="card-content">
              <h1 class="card-title ">Colmar Academy</h1>
              <p class="card-text">It is build on HTML5, CSS. It have responsive</p>
              <p class="card-lang">Language : HTML5, CSS</p>
              <br>
              <a href="https://colmarauto.netlify.app" class="card-link">Website</a>
              <a href="https://github.com/AthipratKanha/AthipratKanha.github.io/tree/main/colmar" class="card-link github-link">Github</a>
            </div>
          </li>
          <li class="card">
            <img class="card-img" src="../assets/work/jam.png" alt="">
            <div class="card-content">
              <h1 class="card-title ">Jamming</h1>
              <p class="card-text">Add playlist to Spotify</p>
              <p class="card-lang">Language : JavaScript(React.js)</p>
              <br>
              <a href="http://autojamming.surge.sh" class="card-link">Website</a>
              <a href="https://github.com/AthipratKanha/Jamming/tree/main/Jamming" class="card-link github-link">Github</a>
            </div>
          </li>
          <li class="card">
            <img class="card-img" src="../assets/work/hat.png" alt="">
            <div class="card-content">
              <h1 class="card-title">Find Your Hat</h1>
              <p class="card-text">Mini Game</p>
              <p class="card-lang">Language : JavaScript</p>
              <br>
              <a href="https://replit.com/@AutoAthiprat/Find-Your-Hat-Test#index.js" class="card-link github-link">Code</a>
            </div>
          </li>
        </ul>
    </div>
</template>




<style>
.works{
  list-style-type: none;
  padding-left: 0;
  text-align: center;
  padding-left: 15%;
  padding-right: 15%;
}

.jp{
  font-weight: 100;
}

.card-lang{
  font-weight: 500;
}

.card {
  display: inline-block;
  margin: 30px 60px;
  width: 350px;
  background: #fff;
  border-radius: 5px;
  box-shadow: 0 2px 5px #ccc;
}
.card-img {
  border-radius: 5px 5px 0 0;
  width: 100%;
  height: 200px;
  object-fit: contain;
}
.card-content {
  padding: 20px;
}
.card-title {
  font-size: 20px;
  margin-bottom: 20px;
  text-align: center;
  color: #333;
}
.card-text {
  color: #777;
  font-size: 14px;
  line-height: 1.5;
}

.card-link{
  border: 2px solid #00aaff;
  text-decoration: none;
  color: #00aaff;
  margin: 0 10px;
  padding: 5px 10px;
  border-radius: 5px;
  transition: 0.4s;
  font-weight: bold;
}
.card-link:hover {
  background-color: #00aaff;
  color: white;
}

.github-link{
  border-color: #171515;
  color: #171515;
}
.github-link:hover {
  background-color: #171515;
  color: white;
}



/*.work-content{
	width: 350px;
	padding: 10px;
	margin: 30px 60px;
  display: inline-block;
}

.work-content:hover{
  background-color: rgba(50, 50, 100, 0.3);
}

.works-image{
    width: 100%;
}*/

@media screen and (max-width: 768px){
  .works{
      padding-left: 1%;
      padding-right: 1%;
  }

  .card-link{
    border: 2px solid #00aaff;
    background-color: #00aaff;
    text-decoration: none;
    color: white;
    margin: 0 10px;
    padding: 5px 10px;
    border-radius: 5px;

    font-weight: bold;
  }

  .github-link{
    background-color: #171515;
    border-color: #171515;
  }
}

@media screen and (max-width: 550px){
  .card{
    width: 280px;
    margin: 30px 0;
  }

  
}
</style>