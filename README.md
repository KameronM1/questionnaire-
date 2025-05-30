<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Drink Preference</title>
    <link rel="stylesheet" href="styles.css">
    
    
</head>



<body>
    <div class="content">
    <header>
        <h1 id="title" >Drink Preference</h1>
        <p id="description">What would be your dream?</p>


    </header>

    <main>
        <p>Get creative, what potential has your drink?</p>
    </main>

    <form name="survey-form" method="post" id="survey-form" action='https://register-demo.freecodecamp.org'>
 
  <fieldset>
        <label id="name-label" for="name">Your Name: 
            <input id="name" type="text" name="name" placeholder="first & last name"  required />
        </label>
    </fieldset>


<fieldset> <label id="email-label">
Please write your email address<input id="email" type="email" placeholder="john.smith@email.com" required/></label>
    </fieldset>

    <fieldset> 
        <label id="number-label" for="age">How old are you? (years): <input id="number" type="number" name="age" min="0" max="119" placeholder="0" required/></label>
</fieldset>

<fieldset>
    <legend>Is your drink with or without gas? </legend>  
      <div  class="radio-group">  <label for="with g">With <input value= "with" id="with g" type="radio" name="gas" class="inline" checked /></label></div>

       <div  class="radio-group">     <label for="without gas"> Without<input value= "without" id="without g" type="radio" name="gas" class="inline" /></label></div>

</fieldset>

<fieldset>

    <legend>Is your drink with or without alcohol?</legend> 
    
    <div  class="radio-group">    <label for="with a">With <input value= "with" id="with a" type="radio"  name="alcohol"  value="1" class="inline" checked /></label></div>

    <div  class="radio-group">    <label for="without a"> Without<input value= "without" id="without a" type="radio" name="alcohol" class="inline" /></label>
    </div>

<br>  <label for="percentage">What percentage alcohol has your drink? <input id="percentage" type="number" name="percentage" min="0" max="99" placeholder= "0%" required/></label>
</fieldset>

<fieldset>
     <label for="container">What container would best fit your dream drink?
          <select id="dropdown" name="container">
            <option value="">(select one)</option>
            <option value="1">Plastic bottle</option>
            <option value="2">Glass bottle</option>
            <option value="3">Can</option>
            <option value="4">Wine bottle</option>
          </select>
        </label>
</fieldset>

<fieldset>
 <label for="Description">Describe your perfect flavour! 
          <textarea id="" name="Description" rows="3" cols="30" placeholder="Cherry and rhubarb with a splash of coconut..." required></textarea>
        </label>
</fieldset>
<fieldset>

 <label for="good-idea">Click here if you think your drink is a good idea?<input type="checkbox" value="good-idea" />
        </label>

</fieldset>
<fieldset>
<label for="terms-and-conditions">I accept the <a href="https://www.freecodecamp.org/news/terms-of-service/">terms and conditions</a>
<input  id="terms-and-conditions" value="terms" type="checkbox" required name="terms-and-conditions" >
      </label>
      </fieldset>
<br>

<label>
<input type="submit" value="Submit" id="submit"/>
</label>
 


</form>

    <footer>
        <p>&copy; 2025 My Website</p>
    </footer>
    </div>
</body>
</html>
