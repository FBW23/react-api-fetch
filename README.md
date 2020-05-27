This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Exercise - Part 2 - Full CRUD

* Implement full CRUD into your app
    * implement create, update, delete of items
    * Do not implement local storage at that point

* Add persistence 
  * componentDidMount
    * After fetching data - store received data in local storage
    * Make sure that you do not fetch data another time in case you have already your data present in local storage
  * Persist all add, edit, delete changes on data with LocalStorage too


## Exercise - Part 1 - DONE

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
