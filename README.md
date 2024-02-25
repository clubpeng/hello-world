# hello-world
This repository is for practising the GitHub Flow
Check out my exercises I've done so far!

<!DOCTYPE html>
  <html>
    <head>
      <title>Buttons</title>
      <style>
        .yellow-button{
        background-color: yellow;
        }

        .orange-button{
        background-color: orange;
        }
      </style>

    </head>

    <body>
      <button>Click</button><br>

      <button>Olivia</button>

      <button>Sandwiches</button><br>

      <p>Hello world!</p>

      <p>I played my bass guitar</p><br>

      <button class = "yellow-button" onclick="alert('Added');">Add to Cart</button>

      <button class = "orange-button" onclick="alert('waiting...');
      alert('purchased');">Buy Now</button><br>

     <button onclick="
      cartQuantity += 4;
      console.log(`Cart Quantity: ${cartQuantity}`);
      ">+4</button>

      <button onclick="
      cartQuantity += 5;
      console.log(`Cart Quantity: ${cartQuantity}`);
      ">+5</button>

      <button onclick="
      cartQuantity--;
      console.log(`Cart Quantity: ${cartQuantity}`);
      ">Remove from Cart</button>

      <button onclick="
      cartQuantity -= 2;
      console.log(`Cart Quantity: ${cartQuantity}`);
      ">-2</button>

      <script>
        let cartQuantity = 0;

        const name = "Olivia";
        console.log('my name is: ' + name);

        const cost = 5 + 2 * 3 + 9;
        console.log(`Cost of Food: $${cost}`);

        const tax = cost * 0.1;
        console.log(tax);

        const totalCost = cost + tax;
        console.log(`Total Cost: $${totalCost}`);
      </script>
    </body>
  </html>
