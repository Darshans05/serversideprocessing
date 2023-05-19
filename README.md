# Design a Website for Server Side Processing

## AIM:
To design a website to perform mathematical calculations in server side.

## DESIGN STEPS:

### Step 1:

clone the repository from github.


### Step 2:

create django admin project.


### Step 3:

start a new app.



### Step 4:

type the programs in the views.py and urls.py.


### Step 5:

create html of suitable forms.



### Step 6:

Publish the website in the given URL.

## PROGRAM :
```html css
<html>
<head>
<meta charset='utf-8'>
<meta http-equiv='X-UA-Compatible' content='IE=edge'>
<title>Area of Triangle</title>
<meta name='viewport' content='width=device-width, initial-scale=1'>
<style type="text/css">
body 
{
background-color:cyan;
}
.edge {
width: 1080px;
margin-left: auto;
margin-right: auto;
padding-top: 200px;
padding-left: 300px;
}
.box {
display:block;
border: Thick dashed lime;
width: 500px;
min-height: 300px;
font-size: 20px;
background-color: purple;
}
.formelt{
color: Red;
text-align: center;
margin-top: 5px;
margin-bottom: 5px;
}
h1
{
color: yellow;
text-align: center;
padding-top: 20px;
}
</style>
</head>
<body>
<div class="edge">
<div class="box">
<h1>Area of a Triangle</h1>
<form method="POST">
{% csrf_token %}
<div class="formelt">
height : <input type="text" name="height" value="{{h}}"></input>(in m)<br/>
</div>
<div class="formelt">
base : <input type="text" name="base" value="{{b}}"></input>(in m)<br/>
</div>
<div class="formelt">
<input type="submit" value="Calculate"></input><br/>
</div>
<div class="formelt">
Area : <input type="text" name="area" value="{{area}}"></input>m<sup>2</sup><br/>
</div>
</form>
</div>
</div>
</body>
</html>
```

## OUTPUT:
![ssp(output)](https://github.com/Darshans05/serversideprocessing/assets/115534676/d0851409-5b33-415c-b5e9-23f21ceee751)

### Home Page:
![ssp(server output)](https://github.com/Darshans05/serversideprocessing/assets/115534676/13309ab0-6e02-40d3-8196-bc9e313a23db)

## Result:
An website to perform mathematical calculations on the server side is successfully completed.

