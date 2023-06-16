<script>
  import heroImage from "../images/heroImage.png";
</script>


<div id="heroAreaContainer">
    <div id="heroAreaLeft">
        Form
    </div>
    <div id="heroAreaRight">
        High quality, eco friendly products from around the world.
    </div>
</div>


<style>

 

  #heroAreaContainer {
    background-color: #000000;
    height: 400px;
    width: 100%;
    background-image: url("../images/heroImage.png");
    background-size:cover;
    background-position:center;
    background-repeat:no-repeat;
    display:flex;
   
  }

 

  #heroAreaLeft {
    flex: 1;
    text-align:center;
    margin-top:auto;
    margin-bottom:auto;
    color: #ffffff;
    font-size:2.5em;  
    text-shadow: 2px 2px 2px rgba(0, 0, 0, 0.3);
  }

  #heroAreaRight {
    flex: 4;
    text-align:center;
    margin-top:auto;
    margin-bottom:auto;
    color: #ffffff;
    font-size: 2.5em;
    text-shadow: 2px 2px 2px rgba(0, 0, 0, 0.3);
  }
</style>
