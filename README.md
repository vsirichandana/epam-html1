# epam-html1
<head>
<link href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">
  <style>
   
  *{
     box-sizing:border-box;
  }
  .wrap{
    max-width:400px;
	margin:auto;
	margin-top:50px;
	padding:20px;
	font-family:sans-serif;
	background:#fff;
	border-radius:10px;
  }
  button{
   padding:10px;
   width:50%;
   margin-bottom:15px;
   box-sizing:border-box;
   border:none;
   font-size:0.7em;
   border-radius:10px;
   font-weight:bold;
  }
  button a{
    text-decoration:none;
	color:#fff;
  }
  button:nth-child(1){
    background:darkblue;
  }
  button:nth-child(2){
    background:red;
  }
  button:nth-child(3){
    background:yellow;
	    margin-top:15px;
  }
  button:hover{
    background:rgba(0,0,0,0.6);
  }
  input[type=text],input[type=password],input[type=submit]{
   width:65%;
   padding:10px;
   margin-bottom:15px;
   font-size:12px;
   border-radius:5px;
   outlin:none;
   border:none;
   border:2px solid gray;
  }
  input[type=submit]{

    background:lightblue;
	border:none;
	border-radius:2px;
	color:#fff;
	font-size:15px;
	padding:15px;
  }
  </style>
</head>
<body>
<div class="wrap">
   <form>
     <center>
	      <h3>Sign In</h3>
          <input type="text" name="uname" placeholder="mail@example.com" >
          <input type="password" name="pass" placeholder="password"><br></br>
		  <input type="submit" value="Sign In" >
		  
    
	 <p><h5>Forgot your password?  &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;     Register!</h5></p>
	 <p><h5>________________or________________</h5></p>
	  </center>
   </form>
   <center>
   <div class="social-media">
      <button><a href="#"><i class="fa fa-facebook"></i></a></button>
	  <button ><a href="#"><i class="fa fa-google"></i></a></button>
	  <button ><a href="#"></a>EPAM LOGIN</button>
   </div>
   <center>
</div>

</body>
