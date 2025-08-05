# upskilling-assignment
<html>
    <head>
        <title>Upskilling</title>
    </head>
    <body style ="background-color: rgb(3, 3, 125);" >
        <table style="background-color: rgba(2, 184, 84, 0.808); 
                     padding-top: 50px;
                     padding-right: 1020px;
                     padding-bottom: 50px; padding-left: 80px;border: 3px, solid, grey;" >
             <thead>
             <th style="background-color: rgb(232, 198, 6);padding-top: 10px;margin-bottom: 50px;"><h3>Upskilling form</h3> </th> 
             </thead>
             <form>
                <tr style="background-color:rgb(232, 198, 6); margin-left: 40px;" >
                      <th>Required fields</th> 
                </tr>
                <tr >
                        <td><label>First name:</label></td>
                        <td><input type="text" name="fName"></td>
                    </tr>
                    <tr>
                        <td><label>Last name:</label></td>
                        <td><input type="text" name="lName" ></td>
                    </tr>
                    <tr>
                        <td><label>Phone</label></td>
                        <td><input type="tel" name="Phone"></td>
                    </tr>
                    <tr>
                        <td><label>Email:</label></td>
                        <td><input type="email" name="email" ></td>
                    </tr>
                 <tr>
                        <td><label>Password:</label></td>
                        <td><input type="password" name="password" ></td>
                    </tr>
             </tbody>
                </table>
                   <table style="background-color: rgba(2, 184, 84, 0.808); padding-top: 50px;
                     padding-right: 1020px;
                     padding-bottom: 50px; padding-left: 80px;border: 3px, solid, grey;" >
                    <thead style="background-color:rgb(232, 198, 6)">
                      <th> Optional fields</th>
                    </thead>
             <tbody>
                <tr>
                    <td>Package:</td>
                    <td><select name="Package:">
                    <option value="" selected disabled>Choose one:</option>
                    <option value="basic">basic</option>
                    <option value="standard">standard</option>
                    <option value="premium">premium</option>
                    </select></td></tr>
                    <tr><td></td>
                    <tr>
                    <td>City:</td>
                    <td><select name="City:">
                    <option value="" selected disabled>Choose one:</option>
                    <option value="Cairo">Cairo</option>
                    <option value="Alex">Alex</option>
                    <option value="others">others</option></select></td>
                    </td></tr>
                    <tr>
                    <td>Gender:</td>
                    <td>female<input type="radio" name="Gender" value="F">
                        male<input type="radio" name="Gender" value="M">
                    </td></tr>
                    <tr>
                    <td>Languages:</td>
                    <td>html<input type="checkbox" name="Languages" value="html">
                        css<input type="checkbox" name="Languages" value="css">
                        js<input type="checkbox" name="Languages" value="js">
                    </td></tr>
                    <tr>
                    <td><label>Fees:</label></td>
                    <td>
                        1000<input type="range" min="1000" max="5000" id="Fees" name="Fees" value="3000">5000</td>
                    </tr>
                    <tr>
                        <td><button type="submit">Register</button></td>
                    </tr>
                </table>
             </form>

    </body>
</html>
    
