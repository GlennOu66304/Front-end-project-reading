# 1.login and sign up project reading:
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
all in container:[All-in-one](https://getbootstrap.com/docs/4.5/layout/overview/)  
```
<div class="container">
```
row:[Basic Structure of a Bootstrap Grid](https://www.w3schools.com/bootstrap/bootstrap_grid_system.asp): it is one part of the bootstrap Grid stucture to tell you row will be created;  
full-height:[full-height](https://www.w3schools.com/howto/howto_css_div_full_height.asp): stretch elements to fit the whole height of the browser window with CSS;  
Justify content:[Justify content](https://getbootstrap.com/docs/4.1/utilities/flex/): put the box into the center;  
other resources:  
[Grid system](https://getbootstrap.com/docs/4.0/layout/grid/)  
```
<div class="row full-height justify-content-center">
```
col-12:[Mix and match](https://getbootstrap.com/docs/4.0/layout/grid/): break a points  
text-center:[Text alignment](https://getbootstrap.com/docs/4.0/utilities/text/): put the text into the center  
align-self-center:[Align self](https://getbootstrap.com/docs/4.0/utilities/flex/#align-items): put the grid into the center  
py-5:[Notation](https://getbootstrap.com/docs/4.0/utilities/spacing/): at top and the bottom to add 5 padding  
other resources:  
[.py](https://www.w3schools.com/bootstrap4/bootstrap_utilities.asp)  
[Bootstrap class: .py-1](https://bootstrapshuffle.com/classes/spacing/py-1+%25_F+py-*-%23)  
[More Spacing Examples](https://www.w3schools.com/bootstrap4/bootstrap_utilities.asp)  

```				
<div class="col-12 text-center align-self-center py-5">
```
pt-sm-2 :[Applying margin top and bottom example](https://www.jquery-az.com/bootstrap-margin-padding-classes-spacing-explained-5-examples/)Add padding top to 2  
[{property}{sides}-{breakpoint}-{size} for sm](https://getbootstrap.com/docs/4.0/utilities/spacing/)  
```

					<div class="section pb-5 pt-5 pt-sm-2 text-center">
```
span:[generic inline container for phrasing content](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/span): higlight certain part of text
W3School:[HTML <span> Tag](https://www.w3schools.com/tags/tag_span.asp)  

```
						<h6 class="mb-0 pb-3"><span>Log In </span><span>Sign Up</span></h6>
```
input:[HTML input element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input):create a square box for inputing
other resources:  
[HTMLinput Tag](https://www.w3schools.com/tags/tag_input.asp)
[HTML Input Types](https://www.w3schools.com/html/html_form_input_types.asp)  
```
			          	<input class="checkbox" type="checkbox" id="reg-log" name="reg-log"/>
```
label:[The HTML label element represents a caption for an item in a user interface.](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/label) a text or content which is next to the input box  
[HTML labelTag](https://www.w3schools.com/tags/tag_label.asp)  
```
			          	<label for="reg-log"></label>	
```	
mx-auto: [Horizontal centering](https://getbootstrap.com/docs/4.0/utilities/spacing/) Maxium Horizontal centering:	          	
```					
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

[Basic Structure of a Bootstrap Grid](https://www.w3schools.com/bootstrap/bootstrap_grid_system.asp)  
Note:  
1.overview file will like open in the browser as raw format;  
2. add the resource link and funxtion into the thoughts on the file to do a quick link.  
3. change the value in the html code by developrt tool and verify it in the Comouted box too.  




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
