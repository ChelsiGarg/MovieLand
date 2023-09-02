<!-- The project is made from https://youtu.be/b9eMGE7QtTk -->
# [LIVE SITE](https://popcorn-and-movieland.netlify.app)

- A basic react project made to understand about states, hooks and props.
- To fetch the movies, I have used an api from [here](https://omdbapi.com/apikey.aspx)

## React concepts used
- Whatever movies are fetched are stored in array *movies*. Since, the movies which are fetched depends on what we are searching for, so the state of *movies* array will change everytime. Hence, I have created a state using *useState* hook & initialized *movies* with empty array
- Similarly *searchTerm* (represents title which we are searching) might also vary as we would be searching for different titles everytime. So, I have created another state for *searchTerm* using *useState* hook & initialized it with empty string.
- I have also used *useEffect* hook which will render only for first time when the component renders. This is made sure by passing an empty array as 2nd argument to it.
