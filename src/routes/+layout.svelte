
<div>
<header id = "header">
<nav>    
    <h1>Welcome to My Page</h1>
    <a id= "home" href="/">Home</a>
    <a id= "about" href="/about">About</a>
    <a id ="furman" href="https://www.furman.edu/">Furman Page</a>
</nav>
</header>

</div>

<div id="logo-box">hello</div>


<style>
 #logo-box{
        border:200px;
        width:100%;
        height:20pxpx;
        background-color:black;
    }

    
#header{
    width:1300px;
    height: 150px;
    background-color:bisque;
    border: 20px;
    padding: 10px 10px;
    text-align: center;
    margin-left: auto;
    margin-right:auto;
}
#home,#about,#furman{
border: none;
  color: white;
  padding: 16px 32px;
  text-align: left;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
  width: 250px;
  margin-left:5px;
  align:left;
  
}
#home{
    background-color:red;
    
}
#furman{
    background-color:purple;
}
#about{
    background-color:blue;
}


</style>


<slot></slot>