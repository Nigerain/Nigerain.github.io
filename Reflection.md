1. When I type in the website, my browser should send out an dns lookup request to try and translate the name into an ip address. After it finds the ip it connect to the github server and pull a  `GET /` reuqest for the main page. GitHub then send an HTTP response with the HTML for `index.html`. After the browser receives the HTML, it parses it and then seit ask for any linked resources, such as my external CSS file and my image in the `/assets` folder. The browser downloads those files, applies the CSS rules to the HTML, and finally renders the page on screen.
2. Docker will contain everything that you need to run it which includes all the dependencies instead of the user needing to download and install it themselves. 
3. I wanted to create a straight horizontal line and I wasn't sure what to search in google so I asked how can I create a  straight line like my resume and put it into chatgpt. I asked this specifically" in html or css how would I create a straight line that goes across the page? I want it to seperate certain sections?"

It gave me this which isn't really an error, but it wasn't what I was looking for:
"
hr {
  border: none;
  height: 1px;
  background-color: #ccc;
  margin: 2rem 0;
}
"
Since I wanted a solid straight black and with smaller margins than what was given. So I had to go and fix the margin and change the color myself