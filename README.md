@import url('https://fonts.googleapis.com/css?family=Open+Sans:400,300,600,700,800|Roboto+Slab:400,300,700');

/* Signin CSS Starts */
.signin-part {
	background: #FFFFFF;
	margin: 0 auto 70px;
	max-height: 350px;
	overflow: auto;
	padding: 30px 30px 70px;
	width: 450px;
	overflow: hidden;
	border-top-width: 5px;
	border-top-style: solid;
	box-shadow: 0 2px 5px 0 rgba(0, 0, 0, 0.1);
	-webkit-box-shadow: 0 2px 5px 0 rgba(0,0,0,.1);
}
.signin-part .signup-link {
	border-top: 1px solid #DDDDDD;
	clear: both;
	overflow: auto;
	padding-top: 15px;
	position: relative;
	text-align: center;
	top: -15px;
}
.signup-link a {
	color: #F0483E;
	display: block;
	text-decoration: underline;
}
#loginform {
	float: left;
	padding: 12px 0px 10px 10px;
	height: 100%;
	position: relative;
	font-weight: 100;
	padding-top: 12px;
}
#loginform table {
	width: 100%;
}
#loginform h3 {
	display: none;
}
#loginform .label {
	font-size: 15px;
	color: #2C2E2F;
	text-align: right;
	padding: 0px 0px 7px 0px;
}
#loginform .input {
	padding: 12px 0px 0px 5px;
	color: #2C2E2F;
	font-size: 1em;
	border-radius: 5px;
	border: 1px solid #E2E2E2;
	width: 100%;
	outline: none;
	box-shadow: none;
	font-weight: 100;
	font-family: HelveticaNeue, "Helvetica Neue", Helvetica, Arial, sans-serif;
	-webkit-box-shadow: 0px 1px 0 rgb(238, 238, 238);
	background-color: #FFF;
	margin-bottom: 10px;
}
#loginform .input:focus {
	outline: 0;
	text-decoration: underline;
	border: 1px solid #009CDE;
	-webkit-box-shadow: none;
	font-family: HelveticaNeue, "Helvetica Neue", Helvetica, Arial, sans-serif;
	-moz-box-shadow: none;
	box-shadow: none;
	background-color: #FFF;
}
.forgotpasslink {
	margin-bottom: 10px;
}
.forgotpasslink span {
	font-size: 0px;
	cursor: pointer;
	color: transparent;
	text-decoration: underline;
}
.forgotpasslink span:hover {
	text-decoration: none;
}
#loginform input[type="submit"], #submit_but_old {
	background-color: #14B45A;
	cursor: pointer;
	border: 1px solid #12AB55;
	margin-top: 10px;
	outline: none;
	padding: 13px 0 16px 0;
	width: 100%;
	text-align: center;
	font-size: 15px;
	font-family: inherit;
	color: #FFF;
	font-weight: bold;
}
#loginform input[type="submit"], #submit_but {
	width: 102%;
	height: 45px;
	padding: 0;
	border: 0;
	display: block;
	background-color: #009CDE;
	-webkit-box-shadow: none;
	-moz-box-shadow: none;
	box-shadow: none;
	-webkit-border-radius: 5px;
	-moz-border-radius: 5px;
	-khtml-border-radius: 5px;
	border-radius: 5px;
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	box-sizing: border-box;
	cursor: pointer;
	-webkit-appearance: none;
	-moz-appearance: none;
	-ms-appearance: none;
	-o-appearance: none;
	appearance: none;
	-webkit-tap-highlight-color: transparent;
	color: #FFF;
	font-size: 1em;
	text-align: center;
	font-weight: 700;
	font-family: HelveticaNeue, "Helvetica Neue", Helvetica, Arial, sans-serif;
	text-shadow: none;
	text-decoration: none;
	-webkit-transition: background-color .4s ease-out;
	-moz-transition: background-color .4s ease-out;
	-o-transition: background-color .4s ease-out;
	transition: background-color 0.4s ease-out;
	-webkit-font-smoothing: antialiased;
}
#loginform .securetxt {
	color: #434343;
	font-size: 12px;
}
#loginform input[type="submit"]:focus, #submit_but:focus {
	outline: none;
	background-color: #008AC5;
}
.msg {
	background-color: #FF6A6A;
	border: 1px solid #E00;
	color: #FFF;
	border-radius: 5px;
	font-family: HelveticaNeue, "Helvetica Neue", Helvetica, Arial, sans-serif;
	display: block;
	font-weight: 500;
	margin: 0 auto;
	padding: 6px 0px;
	text-align: center;
	top: -7px;
	width: 92.3%;
	left: 30px;
	position: relative;
	font-size: 13px;
}
.otheracc-main, .signinusingtxt {
	color: #333;
	float: left;
	font-size: 15px;
	line-height: 34px;
	margin-top: 13px;
	padding-left: 85px;
}
.otheracc-main {
	border-top: 1px solid #FFFFFF;
	float: left;
	height: 30px;
	padding: 5px 10px 0;
}
.otheracc-main font {
	float: left;
	font-size: 11px;
	font-weight: bold;
	margin: 5px 3px 0 0;
}
.GIcon, .GAppsIcon, .YIcon, .FIcon {
	background: none repeat scroll 0 0 #FFFFFF;
	border: medium none !important;
	cursor: pointer;
	float: left;
	height: 30px;
	margin-right: 2px;
}
.google-apps {
	float: left;
	margin-bottom: 20px;
	width: 600px;
}
.GIcon span, .GAppsIcon span, .YIcon span, .FIcon span {
	background-image: url("../images/prd-signin-sprite.png");
}
.GIcon span {
	background-position: left 0;
}
.GIcon span, .GAppsIcon span, .YIcon span, .FIcon span {
	float: left;
	height: 30px;
	width: 40px;
	margin-right: 5px;
}
.GAppsIcon span {
	background-position: -51px 0;
	width: 67px;
}
.YIcon span {
	background-position: -132px 0;
	width: 56px;
}
.FIcon span {
	background-position: -199px 0;
	width: 20px;
}
.GIcon span:hover, .GAppsIcon span:hover, .YIcon span:hover, .FIcon span:hover {
	opacity: 0.8;
}
#gappsDiv {
	margin-left: 50px;
}
.gappfield-main a {
	color: #666;
}
.gapptitle {
	border-bottom: 1px dotted #F5F5F5;
	font-size: 17px;
	margin-bottom: 30px;
	padding: 20px 0 10px;
}
#gappsInputBox {
	padding: 5px;
	width: 305px !important;
}
.www_m {
	color: #12AB55;
	font-size: 17px;
}
.gappbtn + span {
	font-size: 17px !important;
	padding-left: 0 !important;
}
.gappfield-main a {
	font-size: 14px;
}
.gappsub_button {
	text-transform: uppercase;
	font-weight: 600;
	font-size: 17px;
}
/* Signin CSS Ends */
