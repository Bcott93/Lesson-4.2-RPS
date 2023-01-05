# Lesson-4.2-RPS


let choices = ["rock", "paper", "scissors"] // 

let userInput = prompt("rock, paper or scissors - You choose!")

let randomNumber = Math.floor(Math.random() * 3)
console.log(choices[randomNumber])

if ((userInput === choices[0] && randomNumber === 2) || (userInput === choices[1] && randomNumber === 0) || (userInput === choices[2] && randomNumber === 1)) {
    console.log("Win")
}
else if (userInput === choices[randomNumber]) {
    console.log("Draw")
}
else{
    console.log("Lose")
}
