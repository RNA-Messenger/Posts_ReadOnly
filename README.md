# A little Reddit Reader by ANR
 
This is a simple reddit client to browse top posts, done with a modern React stack using hooks for data fetching. I decided not to use any extra libraries to show my abilities as vanilla as possible.

## The Steps I took
 
- I rendered a list of posts using the WithLoader component. It receives a promise and by using hooks I pass the data to the PostsList component in it's props.
- I created different cards for every layout: image, link.
- Every link opens in a new tab in a secure way.
- I implemented a layout using modern SCSS techniques with variables and mixins.
- One media and width restrictions to make the design as responsible as possible.
- A tiny animation for the loader for a nice 'look and feel'.
 
## TODO
 
- A video component, by using the marker "post-hint" I could differentiate reddit-videos from youtube videos and check what other source of videos existed. These markers are not mandatory, so I would've needed a second validation.
- A tiny redux sample.
- Get read off the relative paths.
- Maybe add a dark-mode theme.

## Running the app

First install dependencies

```
npm i
```

To run development server

```
npm start
```

To build for production

```
npm run build
```


## Tools used

- react
- js
- scss
