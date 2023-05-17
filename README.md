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
<title>Area of Rectangle</title>
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
<h1>Area of a Rectangle</h1>
<form method="POST">
{% csrf_token %}
<div class="formelt">
Length : <input type="text" name="length" value="{{l}}"></input>(in m)<br/>
</div>
<div class="formelt">
Breadth : <input type="text" name="breadth" value="{{b}}"></input>(in m)<br/>
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
![Screenshot 2023-05-17 093459](https://github.com/Darshans05/serversideprocessing/assets/115534676/af118e8e-2b47-4379-b233-a543ee12ede8)

### Home Page:
![Screenshot 2023-05-17 093541](https://github.com/Darshans05/serversideprocessing/assets/115534676/b702525a-9abb-4f48-b969-3a8cea55f5d2)


## Result:
An website to perform mathematical calculations on the server side is successfully completed.

