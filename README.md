# Thank you!
This was a really fun assessment and a learning device. I have more experience with Redux Toolkit so going back to vanilla was really great. 
I always find building something from scratch really improves my fundamental understanding, so kudos for having a great assessment. 

- [x] Test cases passing

- [x] hook up your implementation of Dedux to the elemkents in `counter.html`

- [x] have the counter reflect a value stored in your Dedux state

- [x] when the up button is pushed, the counter should increase

- [x] when the down button is pushed, the counter should decrease

- [x] when the reset button is pushed, the counter should reset to zero

- [/] **Bonus**: add a middleware to your store which will persist the latest count 
to localstorage and set up your initial state to use this value


***_almost_** I implemented the middleware to help persiste the latest count but encountered a lot of errors:
 * Everytime I tried to dispatch to localstorage I was saving the previous values.
 * Naive work around was implementing a pseudo reducer, but found it coupled and essentially you are doing work in the reducer. 
 * I found it easier to follow Dan Abromov's methodology of adding localstorage persistance as a subscription.  
