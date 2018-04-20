# getting-started

This repository serves as a sort of playground allowing you to learn by doing.

**Fun Fact**: Git was created by the inventor of Linux, <a href="https://en.wikipedia.org/wiki/Linus_Torvalds">Linus Torvalds</a>.

## Prerequisites

It would be helpful for you to complete this tutorial:
https://try.github.io/levels/1/challenges/1

You'll also need git installed on your machine. Follow the instructions here to get this set up: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

But don't worry, we'll help you along the way.

## Instructions

First, you need to `fork` this repository. You can find that on the top of this page, right under your profile picture.

### Cloning the repository

After you fork this repository, you'll need to get it set up on your local environment. This is accomplished via `git clone`, with the command line. In your repository, you'll find a green button that says "clone or download". Click that, and copy the URL.

Now, in your terminal, where you've installed git, type `git clone https://github.com/YOUR_USERNAME/github-tutorial.git`

Now you have the files downloaded!

### Add changes to files

In `index.html`, add a span, with an id relating to your color, and your name, like so:

```
<span id="color_B9AD83>Name Here</span>
```

You pick a hex color code here: http://htmlcolorcodes.com/, but you can also use the name of the color, if you'd prefer.

After you have added the span in `index.html`, navigate to the `style.css` file, and make some changes to your text!

```
#color_B9AD83 {
  color: #B9AD83;
  font-size: 20px;
}
```

### Commit your changes

After saving your changes, go back to your terminal, and follow these instructions:

1.  `git add .`
2.  `git commit -m "Add name"`
3.  `git push origin master`

### Make a pull request

After you've done the above, go to your repository, and click "New pull request".

You are done!

#### NOTE:

This tutorial may not be as extensive as I'd like it to be. I might have missed some steps. If you've noticed anything, feel free to edit this document, and submit a pull request. Also, if you have trouble with these instructions, or need any help, don't hesitate to reach out to me!
