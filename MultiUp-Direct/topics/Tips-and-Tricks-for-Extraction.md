# Tips and Tricks

## Link Detection

* MultiUp links can be detected in different forms, such as lists, and HTML.

  This means you can copy and paste the contents of a page, or even the HTML of a page to automatically extract all the
  links from the page.
* Link detection also has backwards compatibility with old links, which do not have the same form as the ones generated
  now.
* Duplicate links (i.e. with the same hash) will be ignored, except when links within projects are extracted at the same
  time as the project link.

## Link Selection Behaviour

* Using SHIFT to select links will always select the entire range of links.
* Using CTRL to select links will toggle whether the individual links are selected.
* Deselecting hosts will automatically deselect any selected links with that host, but selecting extra hosts will
  preserve the currently selected links.
* Searching for a file will not deselect any links automatically.
* When you select links, the bar at the bottom will show you how many links you have selected out of the total links
  being displayed.

## Filter Menu

### Validity

These values are provided by MultiUp and are not checked independently.

Valid and Invalid
: Self-explanatory.

Unknown
: These are the links that MultiUp could not check. Links will only appear here if you check
the "Recheck link validity" box.

Unchecked
: These are the links that MultiUp does not report as having a validity. They can be checked by
choosing the "Recheck link validity" box.

### Hosts

- Right-click on a host to quickly select only that host, and deselect all others.
    - This will deselect any links that belong to other hosts.

### Numbers

- The numbers next to each validity and host checkbox indicate the total number of links that have that validity and
  host.
    - Likewise, the number of generated links represents the total number of MultiUp links extracted, including links in
      projects.