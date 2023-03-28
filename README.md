# Eements
Ejemplo
<!DOCTYPE html>
<html lang="en">
<head>
    <title>HTML Elements </title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <!--We can create headings using h1t through h6 as tags.-->
    <h1>A Large Heading</h1>
    <h2>A Smaller Heading</h2>
    <h6>The Smallest Heading</h6>

   <!--The strong and i tags give us bold and italics respectively.--> 
   A <strong>bold</strong> word and an <i>italicized</i> Word!

   <!--We can link to another page (such as cs50´s page) using a.--> 
   View the <a href=""https://cs50.harvard.edu/">CS50 Website</a>!"

   <!--We used ul for an unordered list and ol for an ordered one. both ordered and unordered lists contain li, or list items.-->
   An unordered list:
   <ul>
        <li> Foo</li>
        <li> Bar</li>
        <li> Baz</li>
   </ul>
   An unordered list:
   <ol>
    <li> Foo</li>
        <li> Bar</li>
        <li> Baz</li>
   </ol>

   <!--Images requiere a src atribute, wich can be either the parth to a file on your computeror the link to an imagine online. It also includes an alt atribute, which gives a description in case the image can´t be loaded.-->
   An image:
   <img src="oceano.jpg" alt="Ocean Pacific Picture" width="500">

   <!--We can alos see above that for some elements that don´t contain other ones, closing tags are not necessary.-->

   <!--Here, we use a br tag to  add white space to the page.-->
   <br/><br/>

    <!--A few different tags are necesary to create a table.-->
    <table>
        <thead>
            <tr>
                <th>Ocean</th>
                <th>Average Depth</th>
                <th>Maximum Depth</th>  
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Pacific Ocean</td>
                <td>4,80 mts.</td>
                <td>10,911 mts.</td>
            </tr>
            <tr>
                <td>Atlantic Ocean</td>
                <td>3,646 mts.</td>
                <td>8,486 mts.</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
