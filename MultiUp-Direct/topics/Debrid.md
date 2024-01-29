# Debrid

This tab relates to unlocking links to hosts with a Debrid service.
Supports AllDebrid and RealDebrid.

## Instructions

1. Choose a Debrid service and enter your API key.
    - To automatically load an API key from a file ("Read from file"), create a file called `api_key.json` and enter
      your key using this format:

      <tabs id="Debrid-API-Key-JSON-Format">
      <tab title="All">
         <code-block lang="json">
            {
                "all_debrid": "YOUR_ALLDEBRID_API_KEY",
                "real_debrid": "YOUR_REALDEBRID_API_KEY"
            }
         </code-block>
      </tab>
      <tab title="AllDebrid Only">
         <code-block lang="json">
            {
                "all_debrid": "YOUR_ALLDEBRID_API_KEY"
            }
         </code-block>
      </tab>
      <tab title="RealDebrid Only">
         <code-block lang="json">
            {
                "real_debrid": "YOUR_REALDEBRID_API_KEY"
            }
         </code-block>
      </tab>
      </tabs>

2. Enter the links you want to unlock in the first box.
    - With RealDebrid, there is an option to generate links using remote traffic. Please see the tooltip for more
      details.

3. Click on "Unlock links" to start the process.

4. You can copy the Debrid links using CTRL+C, or use the buttons.
   <tabs id="Copy-Debrid-Links-Format">
      <tab title="Copy">
      URL_1

      URL_2

      URL_3
      </tab>
      <tab title="Copy as \&quot;{URL}\&quot;">
      "URL_1"

      "URL_2"

      "URL_3"
      </tab>
      <tab title="Copy as \&quot;{URL}\&quot; with spaces">
      "URL_1" "URL_2" "URL_3"
      </tab>
      </tabs>