<!DOCTYPE html>
<html >
<head>

    <title>MD MIZANUR RAHMAN</title>
	<link rel="icon" type="image/x-icon" href="favicon.icon">
</head>
    <body>

        <!--table start-->


         <table border="3">
            <tr>
                <td>
                   <!--form 1 start-->
                <form>
                    <b><u><h2>Admission form</h2></u></b>
                    <label for="username">Username:</label>
                    <input type="text" name="username" id="username">
                    <br/>
                    <br/>
                    <label>Password:</label>
                    <input type="password" >
                    <br/>
                    <br/>
                    <label >Gender</label>
                    <input type="radio" name="gender" >
                    <label >Male</label>
                    <input type="radio" name="gender">
                    <label >Others</label>
                    <input type="radio" name="gender">
                    <br/>
                    <br/>
                    <label >Female</label>
                    <label >Hobby</label>
                    <input type="checkbox" >
                    <label >Football</label>
                    <input type="checkbox">
                    <label >Cricket</label>
					<input type="checkbox">
                    <label >Reading book</label>
                    <input type="checkbox">
                    <label >Travelling</label>
                    <br/>
                    <br/>
                    <label >Upload:</label>
                    <input type="file" >
                    <br/>
                    <br/>
                    <label for="address">Address:</label>
                    <textarea rows="3" cols="30"></textarea>
                    <br/>
                    <br/>
                    <label >City:</label>
                    <select>
                        <option value="sydney">Sydney</option>
                        <option value="melbourne">Melbourne</option>
                        <option value="cromwell">Cromwell</option>
                    </select>
                    <br/>
                    <br/>
                    <legend> <u><b> Contact Details:</b></u></legend>
                    <br/>
                    <label>Email Address: </label>
                    <input type="email" >
                    <br/>
                    <br/>
                    <label>Phone Number: </label>
                    <input type="text" >
                    <br/>
                    <br/>
                    <input type="submit" >
                    <input type="reset" >  
                    
                </form>
                       <!--form 1 end-->
              </td>

                <td>
                       <!--form 2 start-->
                    <form >
                        <fieldset>
                            <legend>Personal information :</legend>
                            
                           
                                <label >Name<sup>*</sup>:</label>
                                <input type="text" name="name"  placeholder="Enter your name" required/>
                                <br/>
                                <br/>
                                <label>Email<sup>*</sup>:</label>
                                <input type="email" placeholder="Enter your email" required/>
                                <br/>
                                <br/>
                        
                                <label >Password<sup>*</sup>:</label>
                                <input type="Password" placeholder="make a strong password" required>
                                <br/>
                                <br/>
                                <label >Gender<sup>*</sup></label>
                                <input type="radio" name="gender" >
                                <label >Male</label>
                                <input type="radio" name="gender" >
                                <label >Female</label>
                                <input type="radio" name="gender">
                                <label >other</label>
                                <br/>
                                <br/>
                                <label >Subject<sup>*</sup></label>
                                <input type="checkbox" name="s" >
                                <label >HTML</label>
                                <input type="checkbox" name="s" >
                                <label >CSS</label>
                                <input type="checkbox" name="s" >
                                <label >JS</label>
                                <input type="checkbox" name="s" >
                                <label >PHP</label>
                                <input type="checkbox" name="s" >
                                <label >C</label>
                                <input type="checkbox" name="s" >
                                <label >C++</label>
                                <input type="checkbox" name="s" >
                                <label >Wordpress</label>
                                <br/>
                                <br/>
                                <label >city<sup>*</sup>:</label>
                                <select name="city" >
                                    <option >Natore</option>
                                    <option >Pabna</option>
                                    <option >Bogra</option>
                                    <option >Rajshahi</option>
                                    <option >Singra</option>
                                    <option >Dhaka</option>
                                </select>
                                <br/>
                                <br/>
                                <label >Comment<sup>*</sup>:</label>
                                <textarea name="comment"  cols="30" rows="10"></textarea>
                                <br/>
                                <br/>
                                <label >Upload image<sup>*</sup>:</label>
                                <input type="file" name="image" >
                                <br/>
                                <br/>
                                <label >Date of Birth<sup>*</sup>:</label>
                                <input type="date" name="dob" >
                                <br/>
                                <br/>
                                <input type="submit" >
                                <button type="reset">Reset</button>
                                <br/>
                                <br/>
                           
                            </fieldset>
                        </form>
                          <!--form 2 end-->
                    </td>
                </tr>
        </table>
    </body>
</html>
