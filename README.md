Society of American Archivists at University of Missouri student chapter
======================

Welcome to SAAMUSC on GitHub. Below is our Site Navigation and tips on updating. For more tips see [SinglePaged theme](http://t413.com/SinglePaged) and [datarescue-austin](https://github.com/datarescue-austin/datarescue-austin.github.io)

- **Welcome**
  - [Constitution](pdf)
- Activities
- Officers
- **Join** Us
  - [Twitter](https://twitter.com/SAAMUSC)
  - [Listserv](https://po.missouri.edu/cgi-bin/wa?A0=SAAMUSC-L)
- Resources

Sarah's random tips for updating in the future: in the posts-pages Don't touch the title/bg/color etc. Have the live page open so you can visualize what the text will look like. Keyboard character to make the code text is not the apostrophe but the acute (usu same button as the tilde~. Two hashtag/numbers to Bold. One dash to make a list. Hit an Extra return to exit out of the list back to paragraph text. Insert Hyperlink by: bracketing the words to be hyperlinked then without a space put the link in parentheses. Upload event flyers and/or JPEG's by first uploading it with a simple short filename to our img folder then linking to that concisely with /img/filename.jpg.

Now hop over to [Usage](#usage) to get it running with your own stuff!

**When you publish changes use `git push -u origin gh-pages`**



## Usage

Alright, you've got a clean copy and are ready to push some schmancy pages for the world to ogle at.

- Edit `_config.yml` to change your title, keywords, and description.
- Create a new file in `_posts/` called `2014-01-01-intro.md`
  Edit it, and add:

~~~
  ---
  title: "home"
  bg: white     #defined in _config.yml, can use html color like '#010101'
  color: black  #text color
  style: center
  ---

  # Example headline!
  and so on..
~~~

- Create a second post called `2014-01-02-art.md` with an divider image this time:

~~~
  ---
  title: "Art"
  bg: turquoise  #defined in _config.yml, can use html color like '#0fbfcf'
  color: white   #text color
  fa-icon: paint-brush
  ---

  #### A new section-
~~~

**Note:** That part `fa-icon: paint-brush` will use a font-awesome icon of [paint-brush](http://fortawesome.github.io/Font-Awesome/icon/paint-brush/). You can use any icon from this [font-awesome icon directory](http://fortawesome.github.io/Font-Awesome/icons/).

- install Jekyll with `sudo gem install github-pages`
- run `jekyll serve -w`
  - visit [localhost:4000](http://localhost:4000) to see a live locally served preview.
- Push changes and see them live!




## Changing your colors

- In each post file you can define `bg: mycolor` and `color: myothercolor` to change the background and text colors for that section.
- **mycolor** can be a quoted html color like `'#0fbfcf'` or a key to a special color defined in **_config.yml** under 'colors'.
  - **Note:** Changes to _config.yml require a manual restart to your local server with `^C` and `jekyll serve -w`.

Nifty, right!


