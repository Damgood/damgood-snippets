#View & Control Skeletons
##What goes here?
 - Bare-bones (get it?) forms with processing logic.
   Example: 
   ```
   if(isset($_POST['posted'])){   //FORM HAS BEEN SUBMITTED
   // get the data from the form
    $field1 = $_POST['field1'];
    $field2 = $_POST['field1'];
    $field3 = $_POST['field3'];
    
    //*****************************************
    //validation/sanitization goes here
    //*****************************************
    
    //*****************************************
    //processing/logic goes here
    //*****************************************
    }
    
   <form action="" method="post">
    <label>Field 1 Label:</label>
      <input type="text" name="field1" value="<?php echo $field1; ?>"> <br>
    <label>Field 2 Label:</label>
      <input type="text" name="field2" value="<?php echo $field2; ?>"> <br>
    <label>Field 3 Label:</label>
      <input type="text" name="field3" value="<?php echo $field3; ?>"> <br>
    <input type="submit" name="posted" value="Submit"> <br>
  </form>
            
  ```
