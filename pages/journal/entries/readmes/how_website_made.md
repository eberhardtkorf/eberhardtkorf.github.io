# How This Website Works

### Hosting

This website is hosted using GitHub Pages. The method only allows for static `.html` and `.js` files so the file structure is not as simple as just returning certain files based on the user's request. All the hyperlinks in the `.html` files have to link to another sort of file so it is not possible to dynamically populate a template page with content. Thus, the number of files necessary to make this website possible will grow along with the website. The contents of this website and the file structure it follows can be seen on the following GitHub repository:

[github.com/eberhardtkorf/eberhardtkorf.github.io](https://github.com/eberhardtkorf/eberhardtkorf.github.io)

### Styles

Attempts have been made in order to make the viewing of the content as soft on the eye as possible. A few `.css` things that allow this are listed below:

* Background color is a very subtle off white: #EEEEEE
* Text colour is slighyly more grey than black: #444
* A line height of 1.6 is used
* A font size of 18 is used with the Sans-serif family

### Journal Entries

Journal entries are written in a markdown, `.md`, format and then rendered to view using `zero-md`, a very simple markdown rendering javascript library. Slight adjustments were made to the `.css` files this library uses in order for the rendered files to fit in with the soft theme of the rest of the website.

### Images

Images that are contained within journal entries are uploaded to GitHub as well in order to center them in the final rendered version. An example of this code can be seen below:

`<p align="center">
  <img src="https://raw.githubusercontent.com/eberhardtkorf/eberhardtkorf.github.io/main/pages/journal/entries/readmes/readme_images/test.png" />
</p>`

<p align="center">
  <img src="https://raw.githubusercontent.com/eberhardtkorf/eberhardtkorf.github.io/main/pages/journal/entries/readmes/readme_images/test.png" />
</p>

### Future Work

In order to make this website experience more sleep, a domain will have to be bought and configured to link to this website.


