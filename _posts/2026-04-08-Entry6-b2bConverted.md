# The bits and the bytes

Today's assigmnet was a simple bits and bytes converter. The challenge was shoving it all into a single .html file.
Well, that sounds like it should be simple, and while it sort of was, I did still meet some.. *self-induced obstacles* along the way.

### The conundrum of where to start

It's pretty common that I have an idea that I want to solve, yet have no clue where to actually start and what is viable to use.
In today's case, I simply needed to create a button that would take input from the user, does some simple arithmetic then returns a result.

That *should* be easy, but as usual, Google Searching generally gives a million different options to do it. That once again is not too bad, just pick one, right? Well, spoilers.. **There is a really gods damned easy way to do this,** yet I can assure you that will ***NOT*** be the first option you find.

### Forms

Immediately I was faced with .php as your go-to option to handle html's *forms*. Forms are seemingly the go to way to take input from a user, then process it server-side. Great, how does it work?

It doesn't, not for my usecase. The point of forms is to send the results (submit) to a .php page, where the arguments within the form are handled with *posts* and *gets*. Problem is, **php is not allowed in this assignment, and everything must be in one .html file.**

Okay, so do it with javascript, that's allowed. "Create an eventlistener that listens and shit", that's the internet's advice. Once again, it happens to be overcomplicating a simple problem, and frankly I didn't understand what I was looking at half of the time, nor could I figure out why my eventlistener was not working.

### The simple solulu to the delulu

{% highlight ruby %}
let input = document.getElementById("input");
{% endhighlight %}

Just.. **READ THE INPUT BOX** when you press a button. It's that easy! Why do we have to overcomplicate things with events and listeners when html can literally just read whatever the user types in an input text box?

Anyway. That worked. I now have a "le funny b2b converter".

[Check out the converter repo here.]("https://github.com/CaroFiore/b2b-converter") Perhaps I should make this a link to the html and inmplement it into the blog? :)
