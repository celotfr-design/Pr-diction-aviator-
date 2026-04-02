# Pr-diction-aviator-
Prédiction aviator a 90%
function generateMultiplier() {
  // Simulation proche d’un crash game
  let r = Math.random();
  let multiplier = 1 / (1 - r);
  return Math.min(multiplier, 10).toFixed(2);
}

function playStrategy(rounds = 20, cashout = 2) {
  let balance = 1000;
  let bet = 50;

  for (let i = 1
  
