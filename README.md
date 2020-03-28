# Grocery App

## The exercise

1. You have an App class, which receives a list of products, each one with name and votes. The app should render an unordered list, with a list item for each product. Products can be upvoted or downvoted.
1. By appropriately using React state and props, implement the upvote/downvote logic. Keep the state in the topmost component (App), while the Product component should accept props.

    #### Example
    Passing the following array as products prop to the App `[{ name: "Oranges", votes: 0 }, { name: "Bananas", votes: 0 }]` and clicking the `+` button next to the Oranges should result in HTML like:
```
<div id="root">
  <ul>
    <li>
      <span>Oranges</span> - <span>votes: 1</span><button>+</button> <button>-</button>
    </li>
    <li>
      <span>Bananas</span> - <span>votes: 0</span><button>+</button> <button>-</button>
    </li>
  </ul>
</div>
```

## How to get started

1. Fork the repo - when it's forked the repo name will change to `{your username}/grocery-app_blank`
    * (You might want to rename the repo at this point and remove the `_blank`)
1. Clone the repo
1. `cd` into the repo
1. run `npm install`
1. run `npm start` to run the app in the development mode. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## FYI
`npm run build` builds the app for production to the `build` folder. It correctly bundles React in production mode and optimizes the build for the best performance. The build is minified and the filenames include the hashes.

## Source

This exercise is Question #4 on <a href="https://www.testdome.com/d/react-js-interview-questions/304" target="_blank">Testdome: React Interview Questions</a>
