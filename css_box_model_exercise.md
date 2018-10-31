<!-- From your css_into exercise add the following code to the beginning of your css file.
```css
* {
  margin: 0px;
  padding: 0px;
  border: 1px solid red;
}

```
This is a good visualization of the css box model. Notice how every html element on your page shows up as a red rectangle? When you look at a website and plan a visual layout you should have this in mind.


1. Add a padding of 15px to your h1. Notice that red lines stay together? Experiment with your padding size and see what happens when your change specific padding sides. Exp: padding-left: 50px.

2. Change the width of your h1 tag to a different percentage. -->

3. Now add a margin bottom of 20px to your h1 tag and see what happens. Notice that the red lines separate?

4. Remove the div around the p tag below your h1. Now add a margin-top 20px to your p tag. What changed? Why? Hint: Margins are only concerned about the space around the element as a whole.

5. Experiment giving your li's different margins and paddings. Change their border thickness and color.

6. Look at your page and think about how you could break it down into slightly bigger boxes. This will become a very important design concept especially when working with React. Maybe each ul is it's own section. Each ol it's own. Perhaps all of the contact me is it's own section.

7. In your index.html wrap the different sections you came up with in div tags and change the * {} in your css file to the word div. You should see that you've now broken up the page into more manageable sections. Play around with different widths, margins, paddings, and any other styles you'd like to explore.
