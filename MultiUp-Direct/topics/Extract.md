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
    - Click the "Cancel now" button to cancel any remaining links. You may not see any immediate feedback, but this
      is normal, as MultiUp Direct waits for the links that have already been extracted, but no new links will be
      extracted.

3. Select the links you want. You can do this by:
    - Holding down CTRL to select individual links.
    - Clicking and holding SHIFT to select a range of links.
    - Right-click on a link or selection of links to see more options, such as copying or opening the links in your
      browser.

4. Use the filter menu to narrow down your choices:
    - You can choose which direct links to show based on validity by checking the boxes you want.
    - You can also choose which hosts to show by checking the boxes you want.
    - You can search for files using the search bar.
    - See [this](Tips-and-Tricks-for-Extraction.md#filter-menu) for an explanation of the filter menu