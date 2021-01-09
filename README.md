<!DOCTYPE html>
<html>
<head>
    <title>Login Form</title>
   
</head>
</style>

<body bgcolor="yellow">

    <center>
        <h3>Login Here</h3>

         <form action = "login.php" method="post">
            
             <table>
                <tr>
                     <td>Username:</td>
                      <td>
                         <input type = "text" value = "">
                     </td>
                 </tr>
                 <tr>
                     <td>Password:</td>
                     <td>
                        <input type = "password" value = "">
                     </td>
                 </tr>

                 <tr>
                    <td>Email Id:</td>
                     <td>
                        <input type = "text" value = "">
                    </td>
                </tr>
                <tr>
                    <td>Contact No:</td>
                     <td>
                        <input type = "text" value = "">
                    </td>
                </tr>
                <tr>
                    <td>Gender</td>
                     <td>
                        <input type = "radio" name = "Gender">Male
                        <input type = "radio" name = "Gender">Female
                        <input type = "radio" name = "Gender">Others
                    </td>
                </tr>
                
                  <tr>
                      <td>
                          <input type = "submit" name= "submit" value ="SUBMIT">
                      </td>
                      <td>
                           
                      </td>
                  </tr>
                 <tr>
                     <td>
                        <script>
                            function pop() {
                             alert("Response Submitted");
                            }
                            </script>
                            <button onclick =pop() >
                      
                     </td>
                 </tr>
             </table>
         </form>
    </center>
</body>

</html>
