# SSR

### Why do we need SSR?

you have a React app, which you did not use the `ssr` in your application. If you go to the view page source, you'll see nothing in here, it means that we have to download all the `Javascript and then have to render and then it'll load`,

wouldn't it be better that we download something and show the user something and in the background load the Javascript.

So, server side rendering allows us to write all of our applicaion in React, pre-render everything.

We have to do couple of thiings to prepare for that.
