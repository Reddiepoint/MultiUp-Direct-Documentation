# Extract

This tab relates to extracting direct links to hosts from MultiUp.
Supports `/project/`, `/download/` and `/mirror/` links.

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
4. Select the links you want to use. You can do this by:
    - Holding down CTRL to select individual links.
    - Clicking and holding SHIFT to select a range of links.
5. Right-click on a link or selection of links to see more options, such as copying or opening the links in your
   browser.
6. Use the filter menu to narrow down your choices:
    - "Unknown": These are the links that MultiUp could not check after verification.
    - "Unchecked": These are the links that were not verified by MultiUp. (Links will only appear here if you check
      the "Recheck link validity" box.)
    - "Valid": These are the links that were verified by MultiUp.

[//]: # (3. Click on \"Generate links\" to get the direct links.\n\)

[//]: # (   Click the \"Cancel now\" button to cancel any remaining links. You may not see any immediate feedback, \)

[//]: # (   but this is normal, as MultiUp Direct waits for the links that have already been extracted, \)

[//]: # (   but no new links will be extracted.\n\n\)

[//]: # (4. Select the links you want to use. You can do this by:\n\t\)

[//]: # (- Holding down CTRL to select individual links.\n\t\)

[//]: # (- Clicking and holding SHIFT to select a range of links.\n\n\)

[//]: # (5. Right-click on a link or selection of links to see more options, such as copying or opening the links in
your browser.\n\n\)

[//]: # (6. Use the filter menu to narrow down your choices:\n\t\)

[//]: # (- \"Unknown\": These are the links that MultiUp could not check after verification.\n\t\)

[//]: # (- \"Unchecked\": These are the links that were not verified by MultiUp. &#40;Links will only appear here if
you \)

[//]: # (  do not check the \"Recheck link validity\" box&#41;.\n\t\)

[//]: # (- Hosts: You can choose which hosts you want to see links for. You can right-click on a host and select
\"Select ____ links only\" to quickly filter out the rest.\n\n\)


