<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Babzer</title>
	<!-- <link rel="stylesheet" href="themes/css/babzer.css" /> -->
	<link rel="stylesheet" href="themes/css/jquery.mobile.icons.min.css" />
	<link rel="stylesheet" href="themes/css/jquery.mobile.structure-1.4.5.min.css" />
	<link rel="stylesheet" href="themes/css/style.css" />
	<link rel="stylesheet" href="themes/css/responsive.css" />
	
	<script src="themes/js/jquery-1.11.1.min.js"></script>
	<script src="themes/js/jquery.mobile-1.4.5.min.js"></script>
	<script src="themes/js/custom.js"></script>
	<script src="//cdnjs.cloudflare.com/ajax/libs/require.js/2.1.11/require.min.js"></script>

	<script type="text/javascript" src="cordova-js-master/src/cordova.js"></script>
	<script type="text/javascript" src="js/index.js"></script>	
	<script type="text/javascript">
	document.addEventListener("deviceready",OnDeviceReady,false );	
	function OnDeviceReady()
	{
		alert('Deviceready');
	}
	$(document).ready(function(){ 
		$("#sign_up").click(function(){ 
			alert('ddd');
		});
		
	});
	</script>	
</head>
<body class="app" id="app" onload="onLoad()">
	<div data-role="page" data-theme="a">
		<div data-role="header" data-position="fixed" class="grayHeader">
			<header id="header">
				<div class="headerCont">
					<a href="index.html" class="previous" data-transition="slide">&nbsp;</a>
					<div class="spacer"></div>
				</div>
			</header>
		</div>
		<div data-role="content" data-theme="a">
			<div class="mainSite loginPage signUpPage">				
				<div class="pageBody">
					<div class="pageContainer white" style="padding-top:0;">
						<div class="homeLogo inline">
							<img src="themes/images/logo.png" alt=""/>
						</div>	


						<div class="loginForm">
								<div class="formRow">
									<div class="formFieldBx icon" for="firstName">
										<label class="ico user"></label>
										<input type="text" class="formField" placeholder="First Name" name="firstName" id="firstName"/>
									</div>
								</div>
								<div class="formRow">
									<div class="formFieldBx icon" for="lastName">
										<label class="ico user"></label>
										<input type="text" class="formField" placeholder="Last Name" name="lastName" id="lastName"/>
									</div>
								</div>
								<div class="formRow">
									<div class="formFieldBx icon" for="email">
										<label class="ico email"></label>
										<input type="text" class="formField" placeholder="Email Address"  name="emailAddress" id="email"/>
									</div>
								</div>
								<div class="formRow">
									<div class="formFieldBx icon" for="userPassword">
										<label class="ico user"></label>
										<input type="text" class="formField" placeholder="Password"  name="userPassword" id="userPassword"/>
									</div>
								</div>
								<div class="formRow">
									<div class="formFieldBx icon" for="phone">
										<label class="ico phone"></label>
										<input type="text" class="formField" placeholder="Phone" name="phone" id="phone"/>
									</div>
								</div>
								<div class="buttonset">
									<!-- <input type="submit" class="button lg full" value="Login"/> -->
									<button class="button lg full" id="sign_up">Sign up</button>
								</div>
						</div>
					</div>					
					<div class="connectWith">
						<span class="ttl">or SIGN UP with</span>
						<div class="socialMedia inline">
							<a href="javascript:void(0);">
								<img src="themes/images/fb.png" alt=""/>
							</a>
							<a href="javascript:void(0);">
								<img src="themes/images/tw.png" alt=""/>
							</a>
							<a href="javascript:void(0);">
								<img src="themes/images/gp.png" alt=""/>
							</a>
							<a href="javascript:void(0);">
								<img src="themes/images/li.png" alt=""/>
							</a>
						</div>
					</div>
				</div>	
				<!-- <footer id="footer">
					<a href="javascript:void(0);" class="button lg full">Sign up</a>
					<a href="login.html" class="button lg full blue">Log in</a>
				</footer> -->
			</div>
		</div> 	
<!-- 		<div data-role="footer" data-position="fixed">
			<div class="copyright">
				&copy; 2016-17 WannaPronto LLC<br/>
				All Rights Reserved.
			</div>
		</div>
 -->	</div>
</body>
</html>
