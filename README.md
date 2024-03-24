<!DOCTYPE html>
<html>
<head>
<title>.::: Vivek Resume :::.</title>

</head>
<style>
*{margin:0; padding:0; box-sizing:border-box;}

html {
  height: 100%;  
}

body {
  min-height: 100%;  
  background: #eee;
  font-family: 'Lato', sans-serif;
  font-weight: 400;
  color: #222;
  font-size: 14px;
  line-height: 26px;
  padding-bottom: 50px;
}

.container {
  max-width: 700px;   
  background: #fff;
  margin: 0px auto 0px; 
  box-shadow: 1px 1px 2px #DAD7D7;
  border-radius: 3px;  
  padding: 40px;
  margin-top: 50px;
}

.header {
  margin-bottom: 30px;
  
  .full-name {
    font-size: 40px;
    text-transform: uppercase;
    margin-bottom: 5px;
  }
  
  .first-name {
    font-weight: 700;
  }
  
  .last-name {
    font-weight: 300;
  }
  
  .contact-info {
    margin-bottom: 20px;
  }
  
  .email ,
  .phone {
    color: #999;
    font-weight: 300;
  } 
  
  .separator {
    height: 10px;
    display: inline-block;
    border-left: 2px solid #999;
    margin: 0px 10px;
  }
  
  .position {
    font-weight: bold;
    display: inline-block;
    margin-right: 10px;
    text-decoration: underline;
  }
}


.details {
  line-height: 20px;
  
  .section {
    margin-bottom: 40px;  
  }
  
  .section:last-of-type {
    margin-bottom: 0px;  
  }
  
  .section__title {
    letter-spacing: 2px;
    color: #54AFE4;
    font-weight: bold;
    margin-bottom: 10px;
    text-transform: uppercase;
  }
  
  .section__list-item {
    margin-bottom: 40px;
  }
  
  .section__list-item:last-of-type {
    margin-bottom: 0;
  }
  
  .left ,
  .right {
    vertical-align: top;
    display: inline-block;
  }
  
  .left {
    width: 60%;    
  }
  
  .right {
    tex-align: right;
    width: 39%;    
  }
  
  .name {
    font-weight: bold;
  }
  
  a {
    text-decoration: none;
    color: #000;
    font-style: italic;
  }
  
  a:hover {
    text-decoration: underline;
    color: #000;
  }
  
  .skills {
    
  }
    
  .skills__item {
    margin-bottom: 10px;  
  }
  
  .skills__item .right {
    input {
      display: none;
    }
    
    label {
      display: inline-block;  
      width: 20px;
      height: 20px;
      background: #C3DEF3;
      border-radius: 20px;
      margin-right: 3px;
    }
    
    input:checked + label {
      background: #79A9CE;
    }
  }
}

</style>
<body>
<!---header----->
<link href='https://fonts.googleapis.com/css?family=Lato:400,300,700' rel='stylesheet' type='text/css'>
<!---Introduction----->
<div class="container">
  <div class="header">
    <div class="full-name">
      <span class="first-name">Vivek</span> 
      <span class="last-name">Raj</span>
    </div>
    <div class="contact-info">
      <span class="email">Email: </span>
      <span class="email-val">v*******gmail.com</span>
      <span class="separator"></span>
      <span class="phone">Phone: </span>
      <span class="phone-val">+91-*********</span>
    </div>
    
    <div class="about">
      <span class="position">Full Stack Developer </span>
      <span class="desc">
        I am a Full Stack developer with more than 3 years of experience writing html, css, js ,php ,mysql, laravel & wordpress. I'm motivated, result-focused and seeking a successful team-oriented company with opportunity to grow. 
      </span>
    </div>
  </div>
  <!---Experience----->
   <div class="details">
    <div class="section">
      <div class="section__title">Experience</div>
      <div class="section__list">
        <div class="section__list-item">
          <div class="left">
            <div class="name">ABC</div>
            <div class="addr">DL, IN</div>
            <div class="duration">Nov 2022 - Feb 2023</div>
          </div>
          <div class="right">
            <div class="name">UI developer</div>
            <div class="desc">Software Developer</div>
          </div>
        </div>
                <div class="section__list-item">
          <div class="left">
            <div class="name">ABC</div>
            <div class="addr">GJ,IN</div>
            <div class="duration">Jan 2021 - Feb 2022</div>
          </div>
          <div class="right">
            <div class="name">PHP developer</div>
            <div class="desc">Software Developer</div>
          </div>
        </div>

      </div>
    </div>
	<!---Education----->
    <div class="section">
      <div class="section__title">Education</div>
      <div class="section__list">
        <div class="section__list-item">
          <div class="left">
            <div class="name">Rajasthan Institute of technology</div>
            <div class="addr">RTU, IN</div>
           <div class="duration">Mar 2015 - Mar 2019</div>
          </div>
          <div class="right">
            <div class="name">B.tech</div>
            <div class="desc">Computer Science & Engg.</div>
          </div>
        </div>
        <div class="section__list-item">
          <div class="left">
            <div class="name">High & Secondary High School</div>
            <div class="addr">BR, IN</div>
            <div class="duration">Mar 2011 - Mar 2015</div>
          </div>
          <div class="right">
            <div class="name">10+12th</div>
            <div class="desc">Science</div>
          </div>
        </div>

      </div>
      
  </div>
  <!---Projects----->
     <div class="section">
      <div class="section__title">Projects</div> 
       <div class="section__list">
         <div class="section__list-item">
           <div class="name">CRM FOR ISP</div>
           <div class="text">Frontend html, css, and js.Backend php & mysql.Made for customer data buying,Customer Problem solving. </div>
         </div>
         
         <div class="section__list-item">
                    <div class="name">TOURIST WEBSITE</div>
           <div class="text">Frontend html, css, and js.Backend php & mysql.Made for Pre-booking and variety of room selection in hotel.<a href="#">.</a>
           </div>
         </div>
       </div>
    </div>
	<!----Skills---->
     <div class="section">
       <div class="section__title">Skills</div>
       <div class="skills">
         <div class="skills__item">
           <div class="left"><div class="name"> Frontend</div></div>
           <div class="right"><input  id="ck1" type="checkbox" checked/>
			<label for="ck1"></label><input id="ck2" type="checkbox" checked/>
			<label for="ck2"></label><input id="ck3" type="checkbox" />
			<label for="ck3"></label><input id="ck4" type="checkbox" />
            <label for="ck4"></label><input id="ck5" type="checkbox" />
            <label for="ck5"></label>
			</div>
         </div>
       </div>
	   
       <div class="skills__item">
           <div class="left"><div class="name">Backend</div></div>
           <div class="right"> <input  id="ck1" type="checkbox" checked/>
			<label for="ck1"></label><input id="ck2" type="checkbox" checked/>
			<label for="ck2"></label><input id="ck3" type="checkbox" />
			<label for="ck3"></label><input id="ck4" type="checkbox" />
            <label for="ck4"></label><input id="ck5" type="checkbox" />
            <label for="ck5"></label>
			</div>
         </div>
        </div>
		
	   <!---Interests----->
     <div class="section">
     <div class="section__title"> Interests</div>
       <div class="section__list">
         <div class="section__list-item">
                  Football,Coding,Travelling.
          </div>
       </div>
     </div>
     </div>
  </div>
</div>


</body>
</html>
