# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
   <title>signup</title>
<style>
table ,tr, th, td { 
   border: 3px solid black ; 
   border-collapse: collapse;  
   text-align:center ;
   padding: 10px ;
        }
</style>

</head>
<body>
    <header>
    <p>IN THIS ASSIGNMENT I WOULD BE WORKING ON THE FOLLOWING</p>
   <nav>
 

   <a href="#images"> <li> Implementing HTML5 images </li></a>  
   <a href="#lists"> <li> Implementing HTML5 lists</li></a> 
   <a href="#tables"> <li> Implementing HTML5 tables</li></a>
   <a href="#forms"> <li> Implementing HTML5 forms and input types </li></a>     

  </nav>
     </header>

<main>
    <section id="images">
   <h2> Implementing HTML5 images </h2>
<figure>
     <img src="pexel.jpg" alt="An IPhone image" width="150" height="100" >
     <figcaption>An IPhone image</figcaption>
</figure>
 <p> Another image is displayed here </p>
 <figure>
<img src="pexel2.jpg" alt="Phone accessories" width="150" height="100">
   <figcaption>Some Phone accessories</figcaption>
</figure>
<p>FOR MORE IMAGES </p>
<figure>
 <a href="https://www.pexels.com/"><img src="me.jpg" alt="PEXEL SITE " width="50"></a>
 <figcaption>PEXEL SITE </figcaption>
</figure>
   </section>

   <section id="lists">
   <h2> Implementing HTML5 lists</h2>
   <p>Here are the skills that I have learnt and would love to make furtune from</p>
   <ol style="list-style-type: upper-roman;">
<li>HTML</li>
<li>CSS</li>
<li>PYTHON</li>
<li>Artificial Intelligence and Machine Learning</li>
<li>Also wants to venture into Javascript</li>
   </ol>
  </section>

   <section id="tables">
   <h2>Implementing HTML5 tables</h2>
<table  >
    <thead>
        <tr>
            <th> S/N</th>
            <th> Surn Name</th>
            <th> First Name</th>
            <th> Addresss</th>
            <th> Mobile  </th>
            <th> Emails</th>
        </tr>
    </thead>
    <tbody>
<tr>
    <th>1</th>
    <td>HASSAN</td>
    <td>AHMAD</td>
    <td> F division off Tipper Garage,Ilorin</td>
    <td>07077427778</td>
    <td>ahmad567@email.com</td>
</tr>

<tr>
    <th>2</th>
    <td>SULAIMAN</td>
    <td>HASSAN</td>
    <td>Unilorin Road, Ilorin</td>
    <td>08032223345</td>
    <td>imam234@yahoomail.com</td>
</tr>

<tr>
    <th>3</th>
    <td>ABDURRAHMAAN</td>
    <td>ABDURRASAQ</td>
    <td>Olunlade, Idi Ogede Ilorin</td>
    <td>08156694383</td>
    <td>rasaqi786@email.com</td>
</tr>

<tr>
    <th>4</th>
    <td>ABDUSSALAAM</td>
    <td>RASHEEDAH</td>
    <td>Sanraab, Tanke Ilorin</td>
    <td>08064891498</td>
    <td> abdulsalam@gmail.com</td>
</tr>
    </tbody>
     
</table>

   </section>


   <section id="forms">
   <h2>Implementing HTML5 forms and input types</h2>
        <form action="" method="post"> 
            <fieldset>
                <legend>REGISTRATION FORM</legend>
                <p>
                    <label for="fname">FULLNAME</label>
                    <input type="text" id="fname" name="fullname" placeholder="AHMAD" autocomplete="on" required autofocus>
                </p>
                <p>        
                    <label for="sname">SURNAME</label>
                    <input type="text" id="sname" name="surname" placeholder="HASSAN" autocomplete="on" required>
                </p>
                <p>       
                    <label for="email">EMAIL</label>
                    <input type="email" id="email" name="email" placeholder="ME@gmail.com" autocomplete="on" required>
                </p>  
                <p>       
                    <label for="password">ENTER PASSWORD</label>
                    <input type="password" id="password" name="password" placeholder="ENTER PASSWORD" minlength="8" required>
                </p>  
                <p>         
                    <label for="date">DATE</label>
                    <input type="date" id="date" name="date" required>
                </p>  
                <p>
                    <label for="gender">GENDER</label>
                    <input type="radio" id="male" name="gender" value="male" required> Male
                    <input type="radio" id="female" name="gender" value="female" required> Female
                </p>
                <p>
                    <label for="country">COUNTRY</label>
                    <select id="country" name="country" required>
                        <option value="">Select your country</option>
                        <option value="nigeria">Nigeria</option>
                        <option value="uksa">Saudi Arabia</option>
                        <option value="albania">Albania</option>
                        <option value="pak">Pakistan</option>
                    </select>
                </p>
                <p>
                    <label for="terms">AGREE TO TERMS</label>
                    <input type="checkbox" id="terms" name="terms" required> I agree to the terms and conditions
                </p>
                <p>
                    <input type="submit" value="SIGNUP">
                </p> 
            </fieldset>      

   </form>
   </section>


</main>


<footer>
   



</footer>    
</body>

<footer>
    <p>&copy; 2023 Abu MUsa. All rights reserved.</p>
</footer>

</html>
