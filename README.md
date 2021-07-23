
<p>
  Code Added By Aman Singh: <br><br>
  Files I changed: <b>\src\components\ImageExportDialog.tsx </b>
  Lines at where I changed the code: line 193 - line 231
  What I did:
  <ul>
    <li> Added a export button that will take the image and upload it to the mongoDB database connected via node server </li>
    <li> In the onClick of that export button, I first created a new canvas with all the existing elements on it -> then i converted the canvas to png (using canvastoblob function) -> then sent the png image to backed by making a post request using axios </li>
    <li> Recieved the image and uploaded it to mongodb </li>
    <li> rendered a UI using ejs templating engine in node, <a href="https://github.com/amanscisingh/excaliDrawServer"> link to backend repo <i>(go through the readme file there)</i> </a> </li>
  </ul>
  <br>
  To Run follow these steps:
  <br>
  <b >Step 1: </b>


```bash
npm install
```

<b >Step 2: </b>

```bash
npm start
```
  <br>
  and you are ready to go✌
</p>

#installed dependencied👇
<br>
![image](https://user-images.githubusercontent.com/68449680/126754901-eb24b16a-1808-4168-8a27-09af83c01f57.png)


<hr>




