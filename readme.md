I am going to start adding my web development notes here

10/11/2016
Adding images

Today we are Working on images. The things that could go wrong include:
If the file name is incorrect, the image will not run
If the extension is wrong, the image won't run
If the file type is wrong, the image won't run
ps valid file types include jpg (my-image.jpg)
                            gif (my-imgage.gif)
                            png (my-image.png)
                            svg (my-image.svg)



Cloning a Repository from Github

The Steps include:

1. Fork the Repository
2. Clone your Fork ($ git clone [url])
3. Create a branch (usually this is done using git branch [branch name])
4. Open the folder you want to look at on you editor of choice
5. Things you could do once you have a copy of the repository on your editor include;
replicate the page you want to edit using:
  basic HTML elements (paragraphs, anchors, images, etc.)
  sectioning elements (header, section, article, nav, footer, etc.)
6. Commit your changes appropriately
7. Push your changes (git push --set-upstream origin branch (you can also do git push -u origin master)) You are basically setting up the upstream branch which you have to do when ever you are pushing for the first time.
8. Open a pull request



The HTML Skeleton I have Used for web design looks Something like this

- [Home](#)
- [Products](products.html)
- [About](about.html)
          <li><a href="http://www.google.com">Contacts</a></li>
        </ul>

# This is my first ever headline

## This is my first ever subtitle</h2>

Why do I have to learn these things? Can I just think it and have it appear as a wesite on the web?

Maybe I can! Lemme try #FocusTime

Arranging Boxes on Your Webpage

- Dimensions with Boxes can be tricky but most people do not understand how it works. When you use % (e.g. 100%) you are saying that what ever you are giving a dimension of 100% should basically mirror the dimension of its ancestor. I understand this and I am glad to explain it to anyone who wants to learn more about this.
- When you say auto, you are saying that whatever you assigning a dimension of auto should use all the space available to it i.e. in its immediate environment.
