# Whack-a-Mole

<h1>chatgpt se help</h1>

function randomMole() {
  // Remove the 'mole' class from all elements in the 'squares' array
  squares.forEach(square => {
    square.classList.remove('mole');
  });

  // Generate a random index within the 'squares' array length
  let hitPosition = Math.floor(Math.random() * squares.length);

  // Add the 'mole' class to an element at the randomly generated index
  squares[hitPosition].classList.add('mole');
}

// Call the 'randomMole' function
randomMole();
