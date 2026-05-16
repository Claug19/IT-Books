---
permalink: /Usage
title: "Usage"
---

<link rel="stylesheet" href="Site/Assets/bootstrap.css" />
<div id="readme-top"/>
<nav>
  <h2>
    <a href="IT-Books">BOOKS</a>&nbsp;
    <a href="About">ABOUT</a>&nbsp;
    <a href="Usage">USAGE</a>
  </h2>
</nav>

## Usage

1. Link to github repository: https://github.com/Claug19/IT-Books

2. Clone or download the repository

3. Install Ruby and Bundler, then install the site dependencies:
   `bundle install`

4. Run Jekyll locally from the repository root:
   `bundle exec jekyll serve`

Then open the local URL that Jekyll prints, usually `http://127.0.0.1:4000/`.

5. Add the books to the corresponding subfolder in Books. (must be PDF format)

6. Go inside Scripts and run update to automatically compress and update the boook list. (Requires to be run in Debian based distros)
   - 2.1 You can run compress only.
     `-t` flag specifies the treshold under wich files are not checked for compression
     `--clean` flag deletes the list of files that were already checked then compresses all the files again.
     `--cleanonly` flag only deletes the list of files that were already checked.

   - 2.2 You can run generate_md only to update the list of books.

<p align="right"><a href="#readme-top">(back to top)</a></p>
