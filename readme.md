## Trello To PDF

Renders trello boards as easily-printable webpages.

[>Available here on Github Pages<](https://murolem.github.io/trello-to-pdf/)

Original repo by @arlyon, based on the [brilliant gist](https://gist.github.com/mathiasrw/8710615) by @mathiasrw.

### Usage

Export a board using the right panel [as per these instructions](https://help.trello.com/article/747-exporting-data-from-trello-1).
Then, drag the downloaded file into the UI away you go. You can choose to exclude
lists using the check boxes at the top. They are not included in the final output.

For public boards you can paste the URL into the box and it will load the json automatically.

Alternatively, you can click <a href="javascript:(function(){var loc=location.href;loc=loc.replace('trello.com','murolem.github.io/trello-to-pdf'); window.location.assign(loc)})()">this bookmarklet</a> (drag it to your bookmarks bar!) on any public trello page to instantly get the document for it.
