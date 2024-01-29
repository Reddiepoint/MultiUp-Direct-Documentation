# Extract

This tab relates to extracting direct links to hosts from MultiUp.
Supports `/project/`, `/download/` and `/mirror/` short/long links.

## Instructions

1. Paste your MultiUp links into the first box.
    - Link detection is quite robust and will work with any link that is valid on MultiUp
      (see [link detection](Tips-and-Tricks-for-Extraction.md#link-detection)).
2. Click on "Extract links" to start the extraction process.
    - Checking the "Recheck link validity" box will use MultiUp's API to check the validity of the links.
      However, generation times will be much longer (typically > 30 seconds).
3. Click on "Extract links" to get the direct links.
    - Click the "Cancel now" button to cancel any remaining links. You may not see any immediate feedback, but this
      is normal, as MultiUp Direct waits for the links that have already been extracted, but no new links will be
      extracted.
4. Select the links you want. You can do this by:
    - Holding down CTRL to select individual links.
    - Clicking and holding SHIFT to select a range of links.
    - Right-click on a link or selection of links to see more options, such as copying or opening the links in your
      browser.
    

5. Use the filter menu to narrow down your choices:
    - "Valid" and "Invalid": Self-explanatory.
    - "Unchecked": These are the links that MultiUp does not report as having a validity. They can be checked by
      choosing the "Recheck link validity" box.
    - "Unknown": These are the links that MultiUp could not check. Links will only appear here if you check
      the "Recheck link validity" box.
    - Right-click on a host to quickly select only that host, and deselect all others.
    - You can search for files using the search bar.