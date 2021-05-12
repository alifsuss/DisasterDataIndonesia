# DisasterDataIndonesia

This repo contains a method on scrapping the Indonesian disaster record, stored in disinventar website.
The catch is, since the website is powered by javascript and not follow a simple html when moving around pages, one has to utilise Selenium to "manually" click the next-page button.
For a simple html pages parsing, you can see alifsuss/PegadaianAddress repo, where I only use for-loop to capture all address table in the website.
