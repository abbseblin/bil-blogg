<template>
  <div>
    <div class="main-div">

    <div class="art1">
      <div class="art1-text">
        <div class="art1-h1"><h1>How do combustion <br> engines work?</h1></div>
          <ul class="list1">
            <li>Basics</li>
            <li>Components</li>
            <li>How to service and maintain</li>
          </ul>
          <a class="link1" href="/combustion">Combustion Page</a>
      </div>
        <img class="bild1" src="motor.png" alt="">
    </div>
      

      <div class="art2">
        <div class="art2-text">
          <h1 class="art2-h2">Turbos and superchargers <br> + how they work</h1>
          <ul class="list2">
            <li>What's the Difference Between a Turbocharger <br> and a Supercharger?</li>
            <li>Which Is Better: Turbo- or Supercharger?</li>
            <li>How Much Power Does a Turbo <br> or Supercharger Add?</li>
          </ul>
          <a class="link2" href="/super-turbo">Turbo page</a>
        </div>
        <img class="bild2" src="turbo.png" alt="">
      </div>
      
      <div class="art3">
        <div class="art3-text">
          <h1 class="art3-h3">gasoline vs diesel</h1>
          <ul class="list3">
            <li>Engine Operation</li>
            <li>Fuel injection</li>
            <li>Pros and cons</li>
          </ul>
          <a class="link3" href="/fuel">Fuel page</a>
        </div>
        <img class="bild3" src="bränsle.png" alt="">
      </div>

      <div class="art4">
        <div class="art4-text">
            <h1 class="art4-h4">Cheap ways to increase horsepower</h1>
            <ul class="list4">
              <li>Upgrade the air intake</li>
              <li>Upgrade the exhaust</li>
              <li>Install a performance tuner</li>
            </ul>
              <a class="link4" href="/tuning">Tuning page</a>
            </div>
            <img class="bild4" src="tuning.png" alt="">
      </div>
      
    </div>
  </div>
</template>

<style>
.main-div{
  display: flex;
  flex-direction: column;
  margin-left: 1.5rem;
  margin: 0.625rem;
}
.art1{
  display: flex;
  justify-content:center;
  flex-direction: row;
  margin-left: 300px;
  margin-top: 50px;
  background: rgb(0,0,0);
  background: linear-gradient(90deg, rgba(0,0,0,1) 37%, rgba(178,178,178,1) 100%); 
  width: 700px;
  height: 330px;
  padding-left: 45px;
  padding-bottom: 10px;
  border-radius: 10px;
}
.art1-text{
  order: 0;
  display: flex;
  justify-content:center;
  flex-direction: column;
}
.art1-h1{
  font-size: 2rem;
  margin-bottom:10px ;
  color: whitesmoke;
}
.list1{
margin-left: 15px;
list-style-type: disc;
color: whitesmoke;
}
.bild1{
  width: 300px;
  order: 1;
}
.link1{
  background-color: rgb(251, 191, 36);   
  width: 140px;
  padding: 5px;
  text-align: center;
  margin-left: 20px;
  margin-top: 25px;
}
.link1:hover{
  background-color: rgb(165, 125, 23);
}
.art2{
  display: flex;
  flex-direction: row;
  margin-left: 100px;
  margin-top: 50px;
  background: rgb(0,0,0);
  background: linear-gradient(90deg, rgba(0,0,0,1) 45%, rgba(178,178,178,1) 100%); 
  width: 700px;
  height: 330px;
  padding-left: 45px;
  padding-bottom: 10px;
  border-radius: 10px;
}
.art2-text{
  order: 2;
  display: flex;
  justify-content:center;
  flex-direction: column;
}
.art2-h2{
  font-size: 2rem;
  margin-bottom:10px ;
  color: whitesmoke;
}
.list2{
margin-left: 15px;
list-style-type: disc;
color: whitesmoke;
}
.bild2{
  width: 250px;
  order: 3;
  padding: 30px;
}
.link2{
  background-color: rgb(251, 191, 36);  
  width: 140px;
  padding: 5px;
  text-align: center;
  margin-left: 20px;
  margin-top: 25px;
}
.link2:hover{
  background-color: rgb(165, 125, 23);
}
.art3{
  display: flex;
  justify-content:center;
  flex-direction: row;
  margin-left: 500px;
  margin-top: 50px;
  background: rgb(0,0,0);
  background: linear-gradient(270deg, rgba(0,0,0,1) 30%, rgba(178,178,178,1) 100%); 
  width: 700px;
  height: 330px;
  padding-left: 45px;
  padding-bottom: 10px;
  border-radius: 10px;
}
.art3-text{
  order: 5;
  display: flex;
  justify-content:center;
  flex-direction: column;
}
.art3-h3{
  font-size: 2rem;
  margin-bottom:10px ;
  color: whitesmoke;
}
.list3{
margin-left: 15px;
list-style-type: disc;
color: whitesmoke;
}
.bild3{
  width: 270px;
  order: 4;
  margin-right: 50px;
}
.link3{
  background-color: rgb(251, 191, 36);  
  width: 140px;
  padding: 5px;
  text-align: center;
  margin-left: 20px;
  margin-top: 25px;
}
.link3:hover{
  background-color: rgb(165, 125, 23);
}
.art4{
  display: flex;
  justify-content:center;
  flex-direction: row;
  margin-left: 300px;
  margin-top: 50px;
  background: rgb(0,0,0);
  background: linear-gradient(90deg, rgba(0,0,0,1) 37%, rgba(178,178,178,1) 100%); 
  width: 700px;
  height: 330px;
  padding-left: 45px;
  padding-bottom: 10px;
  border-radius: 10px;
}
.art4-text{
  order: 6;
  display: flex;
  justify-content:center;
  flex-direction: column;
}
.art4-h4{
  font-size: 2rem;
  margin-bottom:10px ;
  color: whitesmoke;
}
.list4{
margin-left: 15px;
list-style-type: disc;
color: whitesmoke;
}
.bild4{
  width: 350px;
  order: 7;
}
.link4{
  background-color: rgb(251, 191, 36);   
  width: 140px;
  padding: 5px;
  text-align: center;
  margin-left: 20px;
  margin-top: 25px;
}
.link4:hover{
  background-color: rgb(165, 125, 23);
}
</style>
