This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Exercise - Fetching data like hell

* Choose an API to fetch data from
  * Easiest: [Typicode](https://jsonplaceholder.typicode.com/)
    * You can find all their APIs if you scroll a bit down to the section "Resources"
  * Or a bit more fruity: [NewsAPI](https://newsapi.org/) (you need to register an API key there first to use the API)
* Create a fresh react app
  * `npx create-react-app yourFancyAppName`
  * Or - if you cloned this repo and want to work in there - do: `npx create-react-app .` 
    * This install an react boilerplate into the current directory
    * It will work if there is just a README file present in the folder
* Go to App.js
  * Clear the default JSX stuff
  * Setup empty state in constructor
  * Add componentDidMount
    * Fetch your API data in there
    * Store the data in state
  * Render a list of your API data into your JSX using map

## Bonus

* Outsource your single API item - e.g. a post in a collection / array of posts - into its own component
* Pass the data down from App.js to that component as prop
