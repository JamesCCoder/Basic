# html

VS Code


<!DOCTYPE html>
<html>
  <head>
    <meta charset = "utf-8">
    <title> this is a website </title>
    <link rel="stylesheet" type="text/css" href="style.css">
    <link rel="icon" type="image/png" href="favicon.png">
  </head>
  
  <body>
    <div>
       <header>
         
         <h1> This is h1 </h1>
         <h2>
           ..
         <h6> This is h6 </h6>
           
         <p> This is a paragraph </p>
           
           Make the <b>words</b> <i>look</i> more beautiful. Here <sub>are</sub> <sup>some</sup> <small>effect</small>.
           
         <a href = "www.google.com" target="_blank"> This is a link </a>
         <hr>
         <img src = "/image/logo.pgn" alt = "Big logo" width = "231" height = "142" />
           
       </header>
      
       <aside>
         
         <table border = "1">
            <thead>
               <tr>
                   <th> header 1 </th>
                   <th> header 2 </th>
               </tr>
            </thead>
            <tbody>
               <tr>
                   <td> row 1, cell 1 </td>
                   <td> row 1, cell 2 </td>
               </tr>
               <tr>
                   <td> row 2, cell 1 </td>
                   <td> row 2, cell 2 </td>
               </tr>
             </tbody>
             <tfoot>
               <tr>
                   <td> row 3, cell 1 </td>
                   <td> row 3, cell 2 </td>
               </tr>
               <tr>
                   <td> row 4, cell 1 </td>
                   <td> row 4, cell 2 </td>
               </tr>
             </tfoot>
         </table>
         
       </aside>  
      
      
    </div>
       <ul>
         <li>Coffee</li>
         <li>Milk</li>
       </ul>
      
       <ol>
          <li>Coffee</li>
          <li>Milk</li>
       </ol>
      
    <div>
        This is a <span> sentence </span>   
      
    </div>
      
    <form>
      First name: <input type = "text" name = "firstname"><br>
      Last name: <input type = "text" name = "lastname"><br>
      Password: <input type = "password" name = "password">
    </form>  
      
    <form>
      <input type = "radio" name = "sex" value = "male"> Male <br>
      <input type = "radio" name = "sex" value = "female"> Female
    </form>  
      
    <form>    
      <input type = "checkbox" name = "vehicle" value = "bike"> I have a bike <br>
      <input tyoe = "checkbox" name = "vehicle" value = "car"> I have a car
    </form>
    
    <form name = "input" action = "html_form_action.php" method = "get">
      username: <input type = "text" name = "username">
      <input type = "submit" value = "submit">
    </form>  
      
    <form action= " ">
      <input type = "button" value = "Hello World!">
    </form>
      
    <form action = " ">
      <select name = "cars">
      <option value = "volve"> Volve </option>
      <option value = "audi"> Audi </option>
      <option value = "pontiac" selected> pontiac </option>
      </select>  
    </form>  
      
    <textarea rows = "10" cols = "30">  
        This is a textarea.
    </textarea>
      
    <h3>send mails to someone@example.com:</h3>
    <form action="MAILTO:someone@example.com" method="post" enctype="text/plain">
    Name:<br>
    <input type="text" name="name" value="your name"><br>
    E-mail:<br>
    <input type="text" name="mail" value="your email"><br>
    Comment:<br>
    <input type="text" name="comment" value="your comment" size="50"><br><br>
    <input type="submit" value="发送">
    <input type="reset" value="重置">
    </form>
      
    <footer>
    </footer>
  </body>  
      
</html>
