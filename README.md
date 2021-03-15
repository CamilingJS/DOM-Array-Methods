# User Wealth Display (DOM-Array-Methods)
## <code>[LIVE VIEW](https://userwealthdisplay.netlify.app/)</code>
### User Wealth display is a project used to diplay knowledge and utility of most commonly used Array Methods
### ➤ First we use fetch api to grab random user information from randomuser.me/api
### ➤ We use async to handle the promises we fetched 
### ➤ The addData fn pushes a new object onto the data and updates the dom
### ➤ The doubleMoney function uses the array.map array method where we used a spread operator to multiply each user.money by 2
### ➤ The sortByRichest function uses the array.sort operator to sort the money objects in descending order (b.money - a.money)
### ➤ The showMillionaires function uses the array.filter operator where it filters user.money by users with money greater than 1000000
### ➤ The calculateWealth functoin uses the array.reduce operator to sum all displayed user.money and display a total



