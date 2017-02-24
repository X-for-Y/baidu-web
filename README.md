# baidu-web
assignment
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>checkbox</title>
    <style>
    .radio-label {
			display: inline-block;
			position: relative;
			height: 20px;
			width: 20px;
			border: 1px #ccc solid;
			border-radius: 50%;
		}
#radio,#checkbox {
			visibility: hidden;
		}
.radio-label input:checked + span {
			position: absolute;
			margin: auto;
			width: 10px;
			top: 50%;
			margin-top: -5px;
			margin-left: -5px;
			left: 50%;
			height: 10px;
			background: red;
			border-radius: 50%;
		}
.checkbox-label {
    		display: inline-block;
			position: relative;
			height: 20px;
			width: 20px;
			border: 1px #ccc solid;
            margin-top: 10px;
}
.checkbox-label input:checked + span {
    		position: absolute;
			border-style: solid;
			border-width: 0 3px 3px 0;
			transform: rotate(45deg);
			border-color: red;
			width: 5px;
			height: 10px;
			top: 50%;
			left: 32%;
			margin-top:-8px; 
}
    </style>
</head>
<body>
    <label for="radio" class="radio-label"> <input type="radio" id="radio" /></label>
    <label for="radio" class="radio-label"> <input type="radio" id="radio" checked/><span></span></label><br>
    <label for="checkbox" class="checkbox-label"> <input type="checkbox" id="checkbox" /></label>
    <label for="checkbox" class="checkbox-label"> <input type="checkbox" id="checkbox" checked/><span></span></label>

</body>
</html>
