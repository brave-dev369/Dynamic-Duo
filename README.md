# Dynamic-Duo


  <h2>Registration Form</h2>

  <form>

      <label for="name">Name:</label>
      <input type="text" id="name" name="name">

      <br><br>

      <label for="email">Email:</label>
        <input type="email" id="email" name="email">

        <br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password">

        <br><br>

        <label for="age">Age:</label>
        <input type="number" id="age" name="age">

        <br><br>

        <label>Gender:</label>
        <input type="radio" name="gender" value="male"> Male
        <input type="radio" name="gender" value="female"> Female

        <br><br>

        <label for="country">Country:</label>
        <select id="country" name="country">
            <option value="">Select Country</option>
            <option value="bangladesh">Bangladesh</option>
            <option value="india">India</option>
            <option value="pakistan">Pakistan</option>
        </select>

        <br><br>

        <label for="message">Message:</label>
        <br>
        <textarea id="message" name="message" rows="5" cols="30"></textarea>

        <br><br>

        <input type="checkbox" id="terms" name="terms">
        <label for="terms">I agree to the terms and conditions</label>

        <br><br>

        <button type="submit">Submit</button>
        <button type="reset">Reset</button>

   </form>
