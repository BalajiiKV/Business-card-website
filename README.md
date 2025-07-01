# Business-card-website
Basic Business Card Website developed using HTML and CSS from scratch without using any AI.

## HTML code
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="styles.css">
    <title>Business Card</title>
</head>

<body>
    <div class="business-card">
        <img class="profile-image" src="https://plus.unsplash.com/premium_photo-1739583707965-b7e985bac889?q=80&w=1267&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="profile-image"/>
       <p class="full-name"><strong>Balaji KV</strong></p>
       <p class="designation">Intern</p> 
       <p class="company">Syncbio Technology</p>
       <hr>
       <p class="email">Email: balajikvofficial@gmail.com</p>
       <p class="phone">Phone: 12345 67890</p>
       <a href="https://in.linkedin.com/in/balajikv29">Portfolio</a>
       <hr>
       
       <div class="social-media">
           <h2>Connect with me</h2>
           <a href="https://in.linkedin.com/in/balajikv29">LinkedIn</a>
           <a href="https://in.linkedin.com/in/balajikv29">GitHub</a>
       </div>
    </div>
</body>

</html>
```
### CSS code
```
body{
background: rosybrown;
font-family: Arial, Helvetica, sans-serif;
padding: 20px;
}
p{
  margin-top: 5px;
margin-bottom: 5px;
}
a{
  text-decoration: none;
}
.business-card{
  width: 300px;
  padding: 20px;
  margin-top: 100px;
  text-align: center;
  font-size: 16px;
  margin-left: auto;
  margin-right: auto;
  background-color: white;
}
.profile-image{
  max-width: 100%;
}
.full-name{
    font-size: 35px;
    margin-top: 10px;
}
.designation{
    font-size: 15px;
    font-style: italic;
    margin-top: 7px;
}
.company{
    margin-bottom: 10px;
}
.email{
    font-style: italic;
    margin-top: 10px;
    color: rgb(104, 92, 92);
    font-size: 15px;
}
```
