<!DOCTYPE html>
<html lang="en">
<head>
  <title>Index</title>
  <style>
textarea   {
  color: blue;
}
button {
  border-color:  red;
  background-color:   black;
  color: white;
padding:  10px;
}
input, select, textarea {
  margin:   10px;
  text-align: center;
}
table {
  background-color: lightgray;
  padding: 20px 10px 10px 20px;
}
p {
  color: blue;
}
</style>
</head>
<body>
<img src="Images/tw_cover_2.png" alt="sample" width="42%">
<h1>This is a heading</h1>
<p>

In the beginning, Tim created the HyperText Markup Language. The Internet

was without form and void, and text was upon the face of the monitor and

the Hands of Tim were moving over the face of the keyboard. And Tim said,

Let there be links; and there were links. And Tim saw that the links were

good; and Tim separated the links from the text. Tim called the links Anchors, and the text He called Other Stuff. And the whole thing together

was the first Web Page.

         </p>

         
         <p>

When your client’s hopping mad,

put his picture in the ad.

If he still should prove refractory,

add a picture of his factory.

</p>
<hr />

<p>

When your client’s hopping mad,<br />

put his picture in the ad.</p>

<p>

If he still should prove refractory,<br />

add a picture of his factory.

</p>
<button value="">Testing
  </button>
<p><a href="Images/tw_cover_2.png" target="_blank" download="tw_cover_2">download</a></p>
<br>
<form action="results.html">
<table>
  <tr>
    <td>
      <label>Enter yourname:</label>
        
    </td>
    <td>
      <input type="text"></input>
    </td>
  </tr>
  <tr>
    <td>
      <label>Enter your age:</label>
    </td>
    <td>
      <input type="number"></input>
    </td>
  </tr>
  <tr>
    <td>
      <label>Choose your gender:</label>
    </td>
    <td>
      <input type="radio" name="gender" value="male" id="male">male</input>
      <input type="radio" name="gender" value="female">female</input>
    </td>
  </tr>
  <tr>
    <td>
      <label>Marital Status:</label>
    </td>
    <td>
      <input type="radio" name="Marital" value="Married">Married</input>
      <input type="radio" name="Marital" value="Unmarried">Unmarried</input>
    </td>
  </tr>
  <tr>
    <td>
      <label>Enter your phone number:</label>
    </td>
    <td>
      <input type="tel" id="phone" name="phone" pattern="[0-9]{5}-[0-9]{5}">
    </td>
  </tr>
  <tr>
    <td>
      <label for="email">Email:</label>
    </td>
    <td>
      <input type="email" id="email" name="email">
    </td>
  </tr>
  <tr>
    <td>
      <label>Password:</label>
    </td>
    <td>
      <input type="password" id="pwd" name="pwd">
    </td>
  </tr>
  <tr>
    <td>
      <label>Choose your city:</label>
    </td>
    <td>
      <select name="city" id="city">
        <option value="1">Chennai</option>
        <option value="2">Salem</option>
        <option value="3">Madurai</option>
        <option value="4">Tiruvannamalai</option>
      </select>
    </td>
  </tr>
  <tr>
    <td>
      <label>
        About yourself
        </label>
    </td>
    <td>
      <textarea name="message" rows="10" cols="30">
        The cat was playing in the garden.
      </textarea>
    </td>
  </tr>
</table>
<br><input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
<label for="vehicle1"> I have a bike</label><br>
<input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
<label for="vehicle2"> I have a car</label><br>
<br><ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
<br>
<ul style="list-style-type:circle">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

<ul style="list-style-type:disc">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

<ul style="list-style-type:square">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
<ul style="line-height:180%">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

<ul style="line-height:80%">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
<ul>
  <li>Coffee</li>
  <li>Tea
    <ul>
      <li>Black tea</li>
      <li>Green tea</li>
    </ul>
  </li>
  <li>Milk</li>
</ul>
<ul>
  <li>Coffee</li>
  <li>Tea
    <ul>
      <li>Black tea</li>
      <li>Green tea
        <ul>
          <li>China</li>
          <li>Africa</li>
        </ul>
      </li>
    </ul>
  </li>
  <li>Milk</li>
</ul>
<br><label for="cfile">Choose</label>
<input type="file" id="cfile" name="cfile">
<br><label for="color">Choose color</label>
<input type="color" id="color" name="color">
<br><input type="submit" value="Submit">
</form>
</body>
</html>
