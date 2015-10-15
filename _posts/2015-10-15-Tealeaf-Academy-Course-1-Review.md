---
published: false
---

As if things hadn't got funky enough with last weeks OOP we changed gears and switched tracks to focus on web development. We got down to the nitty gritty of HTTP, kicked our Blackjack game into shape with Sinatra and added interactivity with Javascript, yew!!

I'd never really given HTTP much thought before. I've done a bit of PHP development but I never really gave the topic much thought, other than when posting a form. Turns out its wholly responsible for the distributed of internet and is so powerful. As an aspiring developer HTTP will occupy a large amount of my time, managing a get request here, a post request there. Understanding HTTP and learning how to process a request and response was the key take away from week 3. HTTP is a stateless protocol and web developers must work with it and perform some clever tricks to make it appear as if it retains state.

Week 3 was really fun. We ported our Blackjack game into a web application using Sinatra, a neat little gem. When you hook up Sinatra with a front end framework, such as Bootstrap, it is a real quick way to create web applications with minimal effort. My previous experience with HTML and CSS was a real bonus here as I could instantly understand the HTML document object model (DOM).

In week 4 I added betting to the Blackjack app. Players could now play for virtual money. Boom! The UX was made a bit more sleek with the addition of some Javascript in the form of jQuery. We also used ajax to create an asynchronous web application. WTF?! is _asynchronous_ I hear you ask... it basically means we can intermittently send data to the server for processing and a response. With this response we can then modify an element on the page without reloading the whole page. Pretty cool.

Here's a little demo of the app..

![Blackjack app]({{site.baseurl}}/_posts/Blackjack-Sinatra.gif)

I also [depolyed it to Heroku](http://sleepy-sea-1270.herokuapp.com). If you fancy giving it a whirl don't bet more than you can afford to loose!![Blackjack-Sinatra.gif]({{site.baseurl}}/_posts/Blackjack-Sinatra.gif)

