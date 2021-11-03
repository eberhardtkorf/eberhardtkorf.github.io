# eberhardtkorf.github.io

## How This Website Was Created

### Hosting

As you can probably see by the url, this website is hosted using GitHub Pages. This method only allows for static `.html` and `.js` files meaning every page has to be in a separate file. This is in contrast to other frameworks such as `Flask` which allows for "template" pages that can be populated with content based on a specific request by the user. The static aspect has the effect that the number of files necessary to make this website possible will grow alongside the website. The contents of this website and the file structure it follows can be seen on my GitHub repository which is configured to be used for GitHub  pages:

[github.com/eberhardtkorf/eberhardtkorf.github.io](https://github.com/eberhardtkorf/eberhardtkorf.github.io)

### Styles

I have opted for a rather simple design which allows for easy reading and looks aesthetically pleasing as well. Some `.css` properties that helped me achieve this are listed below:

* Background color is a subtle off white: #EEEEEE
* Text colour is slightly more grey: #444
* A line height of 1.6 is used
* A font size of 18 is used with the Sans-serif family
* Content is justified to the center of the screen

Feel free to browse my `.css` files to get a deeper understanding for how the style of this website is achieved

### Journal Entries

Journal entries are written in a markdown, `.md`, format and then rendered to view using `zero-md`, a very simple markdown rendering javascript library. Slight adjustments were made to the `.css` files this library uses in order for the rendered files to fit in with the soft theme of the rest of the website.

#### Code

Code blocks in journal entries are rendered with `PrismJS` which comes standard with `zero-md`, however the `.css` files were also modified to use a different theme known as `Nord` and to decrease the font size of the code contained within these blocks.

#### Images

Images that are contained within journal entries are referenced straight from the GitHub repository in order to center them in the final rendered version. According to the markdown philosophy this is not allowed, but it had to be done in order to keep the aesthetic nature of the website. An example of the code that centers an image within a `.md` file is shown below.

```
<p align="center">
  <img src="https://raw.githubusercontent.com/eberhardtkorf/eberhardtkorf.github.io/main/pages/journal/entries/readmes/readme_images/image.png" />
</p>
```

The result:

<p align="center">
  <img src="https://raw.githubusercontent.com/eberhardtkorf/eberhardtkorf.github.io/main/pages/journal/entries/readmes/readme_images/image.png" />
</p>



### Remarks

The next step in the development of this website will be to buy a custom domain which is configured to link to the this GitHub Pages site.





