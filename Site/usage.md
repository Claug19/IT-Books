---
permalink: /Usage
title: "Usage"
---

<link rel="stylesheet" href="Site/Assets/bootstrap.css" />
<div id="readme-top"/>
<nav>
  <h2>
    <a href="https://claug19.github.io/IT-Books/">BOOKS</a>&nbsp;
    <a href="https://claug19.github.io/IT-Books/About">ABOUT</a>&nbsp;
    <a href="https://claug19.github.io/IT-Books/Usage">USAGE</a>
  </h2>
</nav>

## Usage

1. Link to github repository: [https://github.com/Claug19/IT-Books](https://github.com/Claug19/IT-Books)

2. Clone or download the repository

3. Install Ruby and Bundler, then install the site dependencies:
   `bundle install`

4. Add the books to the corresponding subfolder in Books. (must be PDF format)

5. Go inside Scripts and run update to automatically compress and update the book list and site. Also updates the indexes inside the Books folder. (Requires to be run in Debian based distros)
   - 2.1 You can run compress only.
     `-t` flag specifies the treshold under wich files are not checked for compression
     `--clean` flag deletes the list of files that were already checked then compresses all the files again.
     `--cleanonly` flag only deletes the list of files that were already checked.
   - 2.2 You can run generate_md only to update the list of books.
   - 2.3 You can ran generate_site_pages only to update the site structure in Jekyll.
   - 2.4 You can update the folder indexes with generate_book_indexes.

6. To run the site localy, you must first generate the site pages with the `--local` flag
   Run: `./Scripts/generate_site_pages --local`
   Run Jekyll locally from the repository root: `bundle exec jekyll serve`
   Then open the local URL that Jekyll prints, usually `http://127.0.0.1:4000/`.

<p align="right"><a href="#readme-top">(back to top)</a></p>
