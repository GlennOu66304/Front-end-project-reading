# Log In / Sign Up - pure css - #12
## 1.Utilize the [3.Play around with the jQuery:](http://glennou.cn/2020/08/14/Creat-a-Wevbsite-with-a-jQuery/) to process the project fold

## 2.code structure reading:
```
- Log In / Sign Up - pure css - #12
  - css 
   - style.css
  - js
   - script.js
```

## 3.html code:
1.html define:
```
<!DOCTYPE html>
```
2. html language define:
```
<html lang="en" >
```
## 4.head content code reading:  
1.unicde define 
```
<head>
  <meta charset="UTF-8">  
```
2.title display in the url
```
  <title>CodePen - Log In / Sign Up - pure css - #12</title> 
```
3.bootstrap cdn files on the cdnjs to link the bootstrap frameqork,you could refer the link in resources:[twitter-bootstrap The most popular front-end framework for developing responsive, mobile first projects on the web.](https://cdnjs.com/libraries/twitter-bootstrap)  
```
  <link rel='stylesheet' href='https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.5.0/css/bootstrap.min.css'> 
```
4.icon utilizing extrnal resources; you could refer the link in resources:[Start using Unicons Solid](https://iconscout.com/unicons/getting-started/solid)  
```
<link rel='stylesheet' href='https://unicons.iconscout.com/release/v2.1.9/css/unicons.css'>
``` 
5.link the css file in the stylesheetm, you could refer[To link an external stylesheet,](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link)  
```
<link rel="stylesheet" href="css/style.css">

</head>
```
6.[html code comment](https://www.w3schools.com/html/html_comments.asp)  
```
<!-- This is a comment -->
```

## 5. body code content reading:  

### 1.Text on the page(Logo)
```
<body>
<!-- partial:index.partial.html -->
<a href="https://front.codes/" class="logo" target="_blank">
		<img src="https://assets.codepen.io/1462889/fcy.png" alt="">
	</a>
```
### 2.all content:
```
	<div class="section">
```
#### 1.card front: 

##### 1.Email in the codepen section
```
		<div class="container">
			<div class="row full-height justify-content-center">
				<div class="col-12 text-center align-self-center py-5">
					<div class="section pb-5 pt-5 pt-sm-2 text-center">
						<h6 class="mb-0 pb-3"><span>Log In </span><span>Sign Up</span></h6>
			          	<input class="checkbox" type="checkbox" id="reg-log" name="reg-log"/>
			          	<label for="reg-log"></label>
						<div class="card-3d-wrap mx-auto">
							<div class="card-3d-wrapper">
								<div class="card-front">
									<div class="center-wrap">
										<div class="section text-center">
											<h4 class="mb-4 pb-3">Log In</h4>
											<div class="form-group">
												<input type="email" name="logemail" class="form-style" placeholder="Your Email" id="logemail" autocomplete="off">
												<i class="input-icon uil uil-at"></i>
											</div>	
```
##### 2.password in the codepen section
```
											<div class="form-group mt-2">
												<input type="password" name="logpass" class="form-style" placeholder="Your Password" id="logpass" autocomplete="off">
												<i class="input-icon uil uil-lock-alt"></i>
											</div>
```
##### 3.card front: submit button: 
```
											<a href="#" class="btn mt-4">submit</a>

```
##### 4.card front: password reset section:
```
                            				<p class="mb-0 mt-4 text-center"><a href="#0" class="link">Forgot your password?</a></p>
				      					</div>
			      					</div>			      				</div>

```
##### 2.card back:
#### full name section
```							
                              <div class="card-back">
									<div class="center-wrap">
										<div class="section text-center">
											<h4 class="mb-4 pb-3">Sign Up</h4>
											<div class="form-group">
												<input type="text" name="logname" class="form-style" placeholder="Your Full Name" id="logname" autocomplete="off">
												<i class="input-icon uil uil-user"></i>
											</div>
```
#### card back:email section
```	
											<div class="form-group mt-2">
												<input type="email" name="logemail" class="form-style" placeholder="Your Email" id="logemail" autocomplete="off">
												<i class="input-icon uil uil-at"></i>
											</div>	
```
#### card back: password section
```											
											<div class="form-group mt-2">
												<input type="password" name="logpass" class="form-style" placeholder="Your Password" id="logpass" autocomplete="off">
												<i class="input-icon uil uil-lock-alt"></i>
											</div>
```
#### card back: submit button
```
<a href="#" class="btn mt-4">submit</a>
```
```
				      					</div>
			      					</div>
			      				</div>
			      			</div>
			      		</div>
			      	</div>
		      	</div>
	      	</div>
	    </div>
	</div>
```
```
<!-- partial -->
  <script  src="js/script.js"></script>

</body>
</html>
```
## 4.css code:
### 1.css comment code
```
/* Please ❤ this if you like it! */
```
### 2.fonts involve from Google.
```
@import url('https://fonts.googleapis.com/css?family=Poppins:400,500,600,700,800,900');
```
### 3.body css
```
body{
	font-family: 'Poppins', sans-serif;
	font-weight: 300;
	font-size: 15px;
	line-height: 1.7;
	color: #c4c3ca;
	background-color: #1f2029;
	overflow-x: hidden;
}
```
### 4.Text on the page css
```
a {
	cursor: pointer;
  transition: all 200ms linear;
}
a:hover {
	text-decoration: none;
}
```
### 5. unicoon icon css
```
.link {
  color: #c4c3ca;
}
.link:hover {
  color: #ffeba7;
}
```
### 6.Forgot your password? css
```
p {
  font-weight: 500;
  font-size: 14px;
  line-height: 1.7;
}
```
### 7. Login and sign up text css

```
h4 {
  font-weight: 600;
}
h6 span{
  padding: 0 20px;
  text-transform: uppercase;
  font-weight: 700;
}
```
### 8. page area css:

```
.section{
  position: relative;
  width: 100%;
  display: block;
}
```
### 9.
```
.full-height{
  min-height: 100vh;
}
[type="checkbox"]:checked,
[type="checkbox"]:not(:checked){
  position: absolute;
  left: -9999px;
}
```
### 10.
```
.checkbox:checked + label,
.checkbox:not(:checked) + label{
  position: relative;
  display: block;
  text-align: center;
  width: 60px;
  height: 16px;
  border-radius: 8px;
  padding: 0;
  margin: 10px auto;
  cursor: pointer;
  background-color: #ffeba7;
}
.checkbox:checked + label:before,
.checkbox:not(:checked) + label:before{
  position: absolute;
  display: block;
  width: 36px;
  height: 36px;
  border-radius: 50%;
  color: #ffeba7;
  background-color: #102770;
  font-family: 'unicons';
  content: '\eb4f';
  z-index: 20;
  top: -10px;
  left: -10px;
  line-height: 36px;
  text-align: center;
  font-size: 24px;
  transition: all 0.5s ease;
}
.checkbox:checked + label:before {
  transform: translateX(44px) rotate(-270deg);
}
```
### 3d area css
```
.card-3d-wrap {
  position: relative;
  width: 440px;
  max-width: 100%;
  height: 400px;
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
  perspective: 800px;
  margin-top: 60px;
}
.card-3d-wrapper {
  width: 100%;
  height: 100%;
  position:absolute;    
  top: 0;
  left: 0;  
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
  transition: all 600ms ease-out; 
}
```
### front and back card css
```
.card-front, .card-back {
  width: 100%;
  height: 100%;
  background-color: #2a2b38;
  background-image: url('https://s3-us-west-2.amazonaws.com/s.cdpn.io/1462889/pat.svg');
  background-position: bottom center;
  background-repeat: no-repeat;
  background-size: 300%;
  position: absolute;
  border-radius: 6px;
  left: 0;
  top: 0;
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
  -webkit-backface-visibility: hidden;
  -moz-backface-visibility: hidden;
  -o-backface-visibility: hidden;
  backface-visibility: hidden;
}
.card-back {
  transform: rotateY(180deg);
}
```
### checkbox
```
.checkbox:checked ~ .card-3d-wrap .card-3d-wrapper {
  transform: rotateY(180deg);
}
```
### card center css
```
.center-wrap{
  position: absolute;
  width: 100%;
  padding: 0 35px;
  top: 50%;
  left: 0;
  transform: translate3d(0, -50%, 35px) perspective(100px);
  z-index: 20;
  display: block;
}
```
### input box css
```
.form-group{ 
  position: relative;
  display: block;
    margin: 0;
    padding: 0;
}
```
### input box css
```
.form-style {
  padding: 13px 20px;
  padding-left: 55px;
  height: 48px;
  width: 100%;
  font-weight: 500;
  border-radius: 4px;
  font-size: 14px;
  line-height: 22px;
  letter-spacing: 0.5px;
  outline: none;
  color: #c4c3ca;
  background-color: #1f2029;
  border: none;
  -webkit-transition: all 200ms linear;
  transition: all 200ms linear;
  box-shadow: 0 4px 8px 0 rgba(21,21,21,.2);
}
.form-style:focus,
.form-style:active {
  border: none;
  outline: none;
  box-shadow: 0 4px 8px 0 rgba(21,21,21,.2);
}
```
### input-icon(@ and clock) css
```
.input-icon {
  position: absolute;
  top: 0;
  left: 18px;
  height: 48px;
  font-size: 24px;
  line-height: 48px;
  text-align: left;
  color: #ffeba7;
  -webkit-transition: all 200ms linear;
    transition: all 200ms linear;
}
```
### form-group css
```
.form-group input:-ms-input-placeholder  {
  color: #c4c3ca;
  opacity: 0.7;
  -webkit-transition: all 200ms linear;
    transition: all 200ms linear;
}
.form-group input::-moz-placeholder  {
  color: #c4c3ca;
  opacity: 0.7;
  -webkit-transition: all 200ms linear;
    transition: all 200ms linear;
}
.form-group input:-moz-placeholder  {
  color: #c4c3ca;
  opacity: 0.7;
  -webkit-transition: all 200ms linear;
    transition: all 200ms linear;
}
.form-group input::-webkit-input-placeholder  {
  color: #c4c3ca;
  opacity: 0.7;
  -webkit-transition: all 200ms linear;
    transition: all 200ms linear;
}
.form-group input:focus:-ms-input-placeholder  {
  opacity: 0;
  -webkit-transition: all 200ms linear;
    transition: all 200ms linear;
}
.form-group input:focus::-moz-placeholder  {
  opacity: 0;
  -webkit-transition: all 200ms linear;
    transition: all 200ms linear;
}
.form-group input:focus:-moz-placeholder  {
  opacity: 0;
  -webkit-transition: all 200ms linear;
    transition: all 200ms linear;
}
.form-group input:focus::-webkit-input-placeholder  {
  opacity: 0;
  -webkit-transition: all 200ms linear;
    transition: all 200ms linear;
}
```
### submit Button css
```
.btn{  
  border-radius: 4px;
  height: 44px;
  font-size: 13px;
  font-weight: 600;
  text-transform: uppercase;
  -webkit-transition : all 200ms linear;
  transition: all 200ms linear;
  padding: 0 30px;
  letter-spacing: 1px;
  display: -webkit-inline-flex;
  display: -ms-inline-flexbox;
  display: inline-flex;
  -webkit-align-items: center;
  -moz-align-items: center;
  -ms-align-items: center;
  align-items: center;
  -webkit-justify-content: center;
  -moz-justify-content: center;
  -ms-justify-content: center;
  justify-content: center;
  -ms-flex-pack: center;
  text-align: center;
  border: none;
  background-color: #ffeba7;
  color: #102770;
  box-shadow: 0 8px 24px 0 rgba(255,235,167,.2);
}
.btn:active,
.btn:focus{  
  background-color: #102770;
  color: #ffeba7;
  box-shadow: 0 8px 24px 0 rgba(16,39,112,.2);
}
.btn:hover{  
  background-color: #102770;
  color: #ffeba7;
  box-shadow: 0 8px 24px 0 rgba(16,39,112,.2);
}
```
### Big text on the top rignt corner
```
.logo {
	position: absolute;
	top: 30px;
	right: 30px;
	display: block;
	z-index: 100;
	transition: all 250ms linear;
}
.logo img {
	height: 26px;
	width: auto;
	display: block;
}
```
## 5.js code:

## 6.Note:  
1.overview;  
2.add the understanding into the under the code,markdown;  
```
1.copy the code int to the 
2.according to the div area to seprate the code into different area.
3.Utilize the different tags to mark the text.
4.follow the head format to add the thoughts into the code.(Key steps)
5.borrow the Chrome developer tool help you to locate certain part code in the website element:
a.first look for the code in the locattion in the sublime editor;  
b.then go to developer tool to click this postion then it will take you to the position on the page; 
c. or just ctr + f then type the element into the search bar;
```
3.connect them together to read the code;  
4.try to involve the knowledge points in the MDN;
5.utilize the developer tool help you to understand the project file.
6.type all the code by hands again; 

## 7.resources:
code in github:[log-in-sign-uppure-css12](https://github.com/GlennOu66304/Full-stack-project-reading/tree/master/log-in-sign-uppure-css12)  
code in the code pen
[Log In / Sign Up - pure css - #12](https://codepen.io/ig_design/pen/KKVQpVP) 
video:    
[Learn How To Read Code](https://www.youtube.com/watch?v=KnuYHTIIt88)  
Tutorial:  
[How to quickly and effectively read other people’s code](https://selftaughtcoders.com/how-to-quickly-and-effectively-read-other-peoples-code/)  
[How To Read Source Code](https://github.com/aredridel/how-to-read-code/blob/master/how-to-read-code.md)  
[How to read code without ripping your hair out](https://medium.com/launch-school/how-to-read-source-code-without-ripping-your-hair-out-e066472bbe8d)  
[How To Read Code?](https://itnext.io/how-to-read-code-bf478c262932)  






