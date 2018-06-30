# NYT-React-Search

In this activity, i've created a new React-based rendition of the New York Times Article Search application. This assignment hac required me to create React components, work with helper/util functions, and utilize the React mounting lifecycle to query and display articles based on user searches. I've also used Node, Express and MongoDB so that users can save articles to read later.
I've followed the  instructions below:

1 Create a MongoDB database called `nytreact`.

2 Using mongoose, then create an Article schema and model

3 At a minimum, articles should have each of the following fields:

   * `title` (Title of the stored article from nytimes.com)

   * `date` (publish date and time of the article)

   * `url` (URL of the article on nytimes.com)
 

4. Create a Node/Express/MongoDB/ReactJS app called `nytreact`. This will be a recreation of the [NYT Articles Search](https://nytarticle-search-fsf.herokuapp.com/) exercise application we built back in [Week 6](../../../06-ajax/01-Activities/16-NYTSearch/Solved/NYTArticleSearch_Best_Solution/nyt-example.html). Running this application will:

   * Create a Bootstrap layout similar to that displayed in [HW_Assignment.png](HW_Assignment.png). This should be a SPA (Single Page Application) that uses [`react-router-dom`](https://github.com/reactjs/react-router) to navigate, hide and show your React components without changing the route within Express.

   * The layout should include at least two React Components for each page `Home` and `Saved`.

     * **Home** - contains all of the JSX to be rendered on the homepage. This component may contain other smaller components or JSX that renders plain HTML elements. This component should be able to query the NYT API for articles. It displays the results from the API search in a rendered list that displays the article title, publication date, and allows the user to visit an article's url or save the article to the MongoDB.

     * **Saved** - Renders articles that are saved in the MongoDB and allows the user to visit the article's url or delete it from the MongoDB. This page may be made up of multiple smaller components or JSX that renders plain HTML elements.

link to the app: https://nyt-react-search1212.herokuapp.com


