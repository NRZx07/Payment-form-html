# Payment-form-html
it is just a html code for a payment form . you can use this prototype for easy to create.
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Payment form</title>
  </head>
  <body>
    <form action="">
      <h1>payment form</h1>
      <p> required fields are followed by *</p>
      <h2>Contact information</h2>
      <p>Name *:<input type="text" name="name" required /></p>
      <fieldset>
        <p>
          male: <input type="radio" name="gender" id="male" required /> female:
          <input type="radio" name="gender" id="female"  required/>
        </p>
      </fieldset>
      <p> adress : <textarea name="adress" id="adress" cols="5" rows="5"></textarea></p>
      <p> Email *: <input type="email" name="email" id="email" required></p>
      <p> Pincode * : <input type="number" name="pincode" id="pincode" required> </p>
      <hr>
      <h2> paymnet info</h2>
      <p>  card type * : <select name="card_type" id="card_type" required>
        <option value="">- select a card type</option>
        <option value="mastercard">- master card</option>
        <option value="visa">- visa</option>
        <option value="rupay">- rupay</option>


      </select></p>
      <p> card number * : <input type="number" name="number" id="number" required> </p>
      <p> 
        Expiration date * : <input type="date" name="exp-date" id="exp-date" required>
      </p>
      <p> CVV * :<input type="password" name="cvv" id="cvv" required></p>
     <input type="submit" value="Pay now">
    </form>
  </body>
</html>

