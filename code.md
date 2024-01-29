  // if((leftEdge && direction === -1) || (rightEdge && direction === 1)) {
  //   direction = width
  // } else if (direction === width) {
  //   if (leftEdge) direction = 1
  //   else direction = -1
  // }
  // for (let i = 0; i <= alienInvaders.length -1; i++) {
  //   squares[alienInvaders[i]].classList.remove('invader')
  // }
  // for (let i = 0; i <= alienInvaders.length -1; i++) {
  //   alienInvaders[i] += direction
  // }
  // for (let i = 0; i <= alienInvaders.length -1; i++) {
  //   if (!invadersRemoved.includes(i)) {
  //     squares[alienInvaders[i]].classList.add('invader')
  //   }
  // }

  // if(squares[currentShooterIndex].classList.contains('invader', 'shooter')) {
  //   resultsDisplay.innerHTML = 'GAME OVER'
  //   clearInterval(invaderId)
  // }

  // for (let i = 0; i <= alienInvaders.length -1; i++) {
  //   if(alienInvaders[i] > (squares.length - (width -1))) {
  //     resultsDisplay.innerHTML = 'GAME OVER'
  //     clearInterval(invaderId)
  //   }
  // }
}


// function shoot(e) {
//   let laserId
//   let currentLaserIndex = currentShooterIndex
//   function moveLaser() {
//     squares[currentLaserIndex].classList.remove('laser')
//     currentLaserIndex -= width
//     squares[currentLaserIndex].classList.add('laser')
//     if(squares[currentLaserIndex].classList.contains('invader')) {
//       squares[currentLaserIndex].classList.remove('laser')
//       squares[currentLaserIndex].classList.remove('invader')
//       squares[currentLaserIndex].classList.add('boom')

//       setTimeout(() => squares[currentLaserIndex].classList.remove('boom'), 250)
//       clearInterval(laserId)

//       const alienRemoved = alienInvaders.indexOf(currentLaserIndex)
//       invadersRemoved.push(alienRemoved)
//       results++
//       resultsDisplay.innerHTML = results
//       console.log(invadersRemoved)

//     }

//   }
//   switch(e.key) {
//     case "ArrowUp":
//       laserId = setInterval(moveLaser, 100)
//   }
// }

// document.addEventListener('keydown', shoot)
