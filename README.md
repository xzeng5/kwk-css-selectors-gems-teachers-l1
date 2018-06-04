# ARRR Don't Lose Your Gems!

<img src="https://s3.amazonaws.com/after-school-assets/pirate-cat.jpg" alt="pirate cat" width="275" align="right" hspace="10">

It's tough being a clumsy pirate. You trip and fall all the time, your parrot
flies into things, and occasionally (well, more than just occasionally) you even
lose your treasure. Because of all of this, we have to be super careful so
Blackbeard doesn't get even more mad at us. We were just sent on a mission to
pick up some treasure found on the shore of a deserted island. Let's make sure
we get all the gems in our treasure chest!

## Let's Get Started

### Step 1:

Open this lesson in the Learn IDE

### Step 2:

Open `index.html` in the browser by running in terminal `httpserver` and copy
the provided IP to a new Chrome tab.

You're going to code your solution in `css/gems.css`. Go ahead and open that
file in the Learn IDE text editor, as well as `index.html`. Please don't make any
changes to `css/style.css` or to `index.html`.

### Move the Ruby

<img src="images/ruby-gem.png" align="right" width="100px" hspace="10">

Obviously we want to go for the biggest gem first. As a pirate, there is
always the risk of attack by enemy ships. Time is always of the essence, and
the ruby is the biggest stone.

Write the correct selector in `css/gems.css` so that the image tag with
`id="ruby"` is affected.

Once you fill in the selector in `css/gems.css` Save the changes to
`css/gems.css` and refresh in the browser. You should have put the ruby in the
chest. &#10003;

### Move the Emerald

<img src="images/emerald-gem.png" align="right" width="100px" hspace="10">

Emeralds are pretty expensive so we should probably collect that gem next.

In `css/gems.css`, you'll want to replace the text `/*selector for emerald goes
here */` with the CSS selector.

Save the changes to `css/gems.css` and refresh in the browser. Emerald done.
&#10003;

### Move The Yellow Diamond

<img src="images/yellow-diamond-1.png" align="right" width="100px" hspace="10">

Everyone loves a good yellow diamond, so let's make sure we get that gem into
our treasure chest. Again, you'll want to look for any classes or ID's defined
on the yellow diamond image in `index.html`.

Save your changes and refresh in the browser. Yellow diamond complete. &#10003;

### Move the Diamond

<img src="images/diamond-gem.png" align="right" width="100px" hspace="10">

Take a look at `index.html` for any classes or ID's defined on the diamond
image. Use that as your CSS selector in `css/gems.css`.

Diamond done.  &#10003;

### Move The Sapphire

<img src="images/sapphire-gem.png" align="right" width="100px" hspace="10">

We saved the hardest for last, this way if we get attacked now, we can run away
with four gems instead of just one. The sapphire is going to be pretty tricky to
move. There aren't any IDs or classes defined on the `img` tag. But, if you look
carefully, you'll notice the `img` tag linking the sapphire is nested inside of
a `div` with the id `sand`. This `img` tag is known as a child element of the
parent, which is the `div`.

```html
    <div id="sand">
      <img src="images/sapphire-gem.png" alt="Sapphire">
    </div>

```

 In order to select the sapphire image in our CSS, we can use what's called a
descendant selector. In `css/gems.css` you'll want to replace the text
`/*selector for sapphire goes here */ ` with `#sand img`.

`#sand img` is our CSS selector. This selector will first look for an HTML tag
with the ID `sand`, and from there, look for the `img` child HTML element, and
apply that styling to the `img`.

Sapphire.  &#10003;

