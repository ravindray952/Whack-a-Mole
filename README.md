# Whack-a-Mole

>chatgpt se help

```
function randomMole() {
  // Remove the 'mole' class from all elements in the 'squares' array
  squares.forEach(square => {
    square.classList.remove('mole');
  });            ```


``
  // Generate a random index within the 'squares' array length
  let hitPosition = Math.floor(Math.random() * squares.length);

  // Add the 'mole' class to an element at the randomly generated index
  squares[hitPosition].classList.add('mole');
}   ```



// Call the 'randomMole' function
randomMole();   

              





function randomMole(){
      squares.forEach(square => {
        square.classList.remove('mole');
})

   let randomSquare =squares[Math.floor(Math.random()
   *squares.length)]; 
   randomSquare.classList.add('mole');   
    hitPosition = randomSquare.id;            
}

randomMole();

squares.forEach(square =>{
    square.addEventListener('mousedown', () => {
        if(square.id === hitPosition) {
            scrore++;
            scoreH2.innerText = 'Your Score ${score}';
            hitPosition = null;
        }  

                           ```
