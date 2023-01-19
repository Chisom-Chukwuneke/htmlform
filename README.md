<!DOCTYPE html>
  <html>
    
      <head>
        <title> HTML Form </title>
    </head>
    
    <body>
        <h1><span style="color: #993300;"><u>STUDENT REGISTRATION FORM</u></span></h1>
        <form>
            <table cellspacing="15">
                <tbody>
                    <tr>
                        <td>
                            <label for="avatar"><b> Upload your picture: </b></label></td>
                         <td> 
                            <input type="file" id="avatar" 
                           accept="image/png, image/jpeg" required></td>
                    </tr> 
                       
                        <tr>
                            <td> <label> <b>First Name: </b></label></td>
                            <td> <input type="text" required></td>   
                        </tr>  

                    <tr>
                        <td>
                            <label> <b>Last Name: </b></label> </td>
                        <td>
                         <input type="text" required> </td>
                     </tr>
            
                    <tr>
                        <td>
                        <label><b>Date of Birth:</b></label></td>
                        <td>
                        <input type="date"  value="2018-07-22" required></td>
                    </tr>

                    <tr> 
                        <td><b><label for="email">Email ID:</b></label></td>
                    <td>
                        <input type="email" id="email"
                        pattern=".+@globex\.com" size="30" required></td>
                    </tr>

                    <tr>
                        <td> <label for="phone"><b>Phone Number:</b></label></td>
                        <td><input type="tel" id="phone" name="phone"
                        pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}" required> <small> (11 digit number)</small></td>
                    </tr>
           
                    <tr>
                        <td><legend><b>Gender:</b></legend>   </td>
                        <td><input type="radio" name="gender"> <label>Male</label>
                             <input type="radio" name="gender"> <label>Female</label></td>
                    </tr>         
            
                    <tr>
                        <td>    <label><b> Address: </b></label>   </td>
                        <td>    <textarea cols="30" rows="2"> </textarea> </td>
                     </tr>    
            
                    <tr> 
                        <td>    <label><b> City: </b></label> </td>
                        <td>    <input type="text" required> </td>
                     </tr>

                    <tr>
                        <td>    <label><b> State: </b> </label> </td>
                        <td>    <input type="text" required>    </td>
                     </tr>

                    <tr> 
                        <td>    <label><b> Country: </b></label>  </td>
                        <td> <input type="text" required>   </td>
                     </tr>

                    <tr>
                    <td>    <label for="pass"><b>Password </b><br>(8 characters minimum):</label> </td>
                    <td> <input type="password" id="pass" minlength="8" required>   </td>
                     </tr> 

                    <tr> 
                    <td>    <legend><b>Hobbies:</b></legend>   </td>
            
                    <td><div>
                        <input type="checkbox" >
                        <label> Dancing </label>
                        </div> 

                     <div>
                    <input type="checkbox" >
                    <label> Singing </label>
                  </div>    

                     <div>
                    <input type="checkbox" >
                    <label>Reading </label>
                  </div>   

                    <div>
                    <input type="checkbox" >
                    <label> Others </label> 
                    <input type="text">
                  </div>   </td>        
                    </tr>

                    <tr>
                        <td>    <label><b>WAEC GRADES:</b>  </label> </td>
                        <td>    <label> Subjects: </label> </td>
                        <td>    <label> Grades: </label> </td>
                        <td>    <label> How Many Sittings: </label> </td>
                     </tr>

                     <tr>
                        <td>    <label>  </label> </td>
                        <td>    <label> 1. English </label> </td>
                        <td>    <input type="text" required>  </td>
                        <td>    <input type="text" required>  </td>
                     </tr>

                     <tr>
                        <td>    <label>  </label> </td>
                        <td>    <label> 2. Mathematics </label> </td>
                        <td>    <input type="text" required>  </td>
                        <td>    <input type="text" required>  </td>
                     </tr>

                     <tr>
                        <td>    <label>  </label> </td>
                        <td>    <label> 3. Biology </label> </td>
                        <td>    <input type="text" required>  </td>
                        <td>    <input type="text" required>  </td>
                     </tr>

                     <tr>
                        <td>    <label>  </label> </td>
                        <td>    <label> 4. Chemistry </label> </td>
                        <td>    <input type="text" required>  </td>
                        <td>    <input type="text" required>  </td>
                     </tr>

                     <tr>
                        <td>    <label>  </label> </td>
                        <td>    <label> 5. Physics </label> </td>
                        <td>    <input type="text" required>  </td>
                        <td>    <input type="text" required>  </td>
                     </tr>

                    <tr>
                        <td>    <legend><b>Course Applied for: </b></legend>   </td>
                    <td> <input type="radio" name="course"> <label>Medicine</label>
                     <input type="radio" name="course"> <label>Nursing</label>
                     <input type="radio" name="course"> <label>Medical Laboratory</label>
                    <input type="radio" name="course"> <label>Micro Biology</label> </td>
                    </tr>
                </tbody> 
            </table> <br><br>
                    <input type="submit">
                    <input type="submit" value="Reset">
        </form>
    </body>
    
    
    
</html>
