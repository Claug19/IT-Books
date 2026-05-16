<link rel="stylesheet" href="Assets/bootstrap.css" />
<div id="readme-top"/>
<nav>
  <h2>
    <a href="README.md" data-jekyll-path="/">BOOKS</a>&nbsp;
    <a href="ABOUT.md" data-jekyll-path="/about/">ABOUT</a>&nbsp;
    <a href="USAGE.md" data-jekyll-path="/usage/">USAGE</a>
  </h2>
</nav>
<script>
  document.querySelectorAll("a[data-jekyll-path]").forEach(function (link) {
    link.href = link.dataset.jekyllPath;
  });
</script>

## Usage

1. Link to github repository: https://github.com/Claug19/IT-Books

2. Clone or download the repository

3. Add the books to the corresponding subfolder in Books. (must be PDF format)

4. Go inside Scripts and run update to automatically compress and update the boook list. (Requires to be run in Debian based distros)
   - 2.1 You can run compress only.
     `-t` flag specifies the treshold under wich files are not checked for compression
     `--clean` flag deletes the list of files that were already checked then compresses all the files again.
     `--cleanonly` flag only deletes the list of files that were already checked.

   - 2.2 You can run generate_md only to update the list of books.

<p align="right"><a href="#readme-top">(back to top)</a></p>
