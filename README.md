# Dark Echoes

![The application shows a list of episodes of a TV series. A detailed description is shown for a selected episode.](./example.png)

Let's build a TV app with React! Users will be able to browse the episodes of a fictional TV series named _Dark Echoes_.

## Requirements

The boilerplate for setting up a React app with Vite has already been provided for you. You can start the app by running `npm install` and `npm run dev`.

Your task is to complete the `<App>` component in `src/App.jsx` to render the data that is exported from `src/data.js`. Your submission should meet the following requirements:

- The app imports the array from `data` into a state variable.
  // import an array froom teh data src and turn it into a state variable
- The app keeps the selected episode in a state variable.
  // the variable that is selected stays in a state until changed
- A list of episode names is rendered.
  // a list (li) of all the episodes names and render it
- Each item in the rendered list has a unique key.
  // each item in th elsit hgas. auniqe key.
- When an episode in the list is clicked, the selected episode is updated in state.
  // use onclick funtion when an episode in the list is clicked.
- If no episode is selected, the app shows a message encouraging the user to select an episode.
  // returning dunction is no episode is clicked show message " make sure you select an episode"
- If there is a selected episode, the app displays more details about it, including the episode's number, name, and description.
  // return selected episdoe form users input and return its name, number and description and render it.
- UI elements are organized into component functions.
- The app is styled with CSS.
  // style with css

## Submission

Please submit the link to your public GitHub repository.
