---
name: Stylesheets
about: Stylesheets
title: Stylesheets
labels: enhancement, good first issue, help wanted
assignees: ''

---

.message {
	margin-bottom: 20px;
	border-width: 1px;
	border-style: solid;
}
.message-wrapper:after {
	content: '';
	display: table;
	clear: both;
}
.message-wrapper { 
	position: relative;
	margin-right: 20px;
	padding: 10px;
	background: #fff;
	min-height: 20px;
}
.message-icon {
    background: none;
}
.message-icon:before {
	content: '';
	position: absolute;
	top: 10px;
	left: 10px;
	width: 20px;
	height: 20px;
	display: block;
    font: normal normal normal 20px/20px FontAwesome;
	text-align: center;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
.message-information { 
	padding: 1px 0 0 25px;
    text-align:left;
}
.message-information a { text-decoration: underline; }
.message-title {
	font-weight: bold;
	text-transform: uppercase;
}
/* override newegg.css */
.message-icon {
	float: none;
	width: auto;
	height: auto;
	background: none;
}
.message-information,
.message-title {
	color: inherit;
	font-size: inherit;
}
.message-note { color: inherit; }
/* style */
.message-note {
	border-color: #e1b06a;
	background-color: #e1b06a;
}
.message-note .message-icon:before {
	content: "\f069";
	color: #e1b06a;
}
.message-alert { 
	border-color: #cc0000;
	background-color: #cc0000;
}
.message-alert .message-icon:before {
	content: "\f071";
	color: #cc0000;
}
.message-info {
	border-color: #e1b06a;
	background-color: #e1b06a;
}
.message-info .message-icon:before {
	content: "\f05a";
	color: #e1b06a;
}
.message-promo {
	border-color: #758d19;
	background-color: #758d19;
}
.message-promo .message-icon:before {
	content: "\f005";
	color: #758d19;
}
.message-success {
	border-color: #7ab677;
	background-color: #7ab677;
}
.message-success .message-icon:before {
	content: "\f058";
	color: #7ab677;
}

.message-alert em { 
	color: #cc0000; 
	font-style: normal;
}
.message-note em,
.message-info em { color: #e1b06a }
.message-promo em { color: #758d19 }
