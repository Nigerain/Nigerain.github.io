1. Flex-direction controls how items inside a flex container are arranged. If I use flex-direction: row, the items will be placed horizontally from left to right. This helps for things like navigation bars where links should appear side by side. In my website I used this behavior in the navbar so my name stays on the left and the navigation links appear next to each other.

If I use flex-direction: column, the items are stacked vertically from top to bottom. This is useful when I want elements to appear on separate lines. I used this in the header section so my profile image appears first, and then my name and contact information appear underneath it.

2. I think relative units are important for responsive design because they allow elements to scale up or down depending on the screen size. If everything is set using fixed pixel values, the layout might look fine on a my monitor but could look too big or cramped on a phone.

Units like %, vh, or rem scale relative to the screen or font size, which helps the layout adapt to different devices. This makes the website easier to read and use on phones, tablets, and desktops.

3. One thing I used AI for was figuring out how to structure the header layout using flexbox. I originally tried using display: flex on the header, but everything inside the header ended up appearing on the same row. This included my profile image, name, ontact information, and the horizontal line. Which messed up my layout since I wanted because I wanted the image on its own line and the text underneath it.

The AI told me to use flex-direction: column so the elements would stack vertically instead of appearing side by side.

.hero {
  display: flex;
  flex-direction: column;
}

But this caused another issue where the horizontal line didn't go all the way across so I had to change it and make it so it did.