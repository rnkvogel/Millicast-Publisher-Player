# Millicast-Publisher-Player
Customizable Millicast Publisher Player

Millicast Audio Only Player can be set.

This is a customizable publisher and player that can be used on your web site for 1 to many real time live streams. Live streams to all devices.

You will need a Millicast account to get started. https://millicast.com/

Once you have created a Millicast account you will need to create a live stream token.
If you would like to use the DEMO make sure the token is for any(*) name.


DEMO: https://rnkvogel.github.io/Millicast-Publisher-Player/publisher/

In your Millicast portal(+) Add a new token and Make sure to select Use ANY name * for this set up!!!!!! Security options can be set up with this example using the Millicast API.
Download the files. Open these files with a text editor.

Open the JS/Publisher.js file.
Open the JS/viewer.js file. EDIT THE FOLLOWING
let accountId = ''YOURID'; //let accountId ADD YOUR ACCOUNT ID HERE

let token ="REPLACE WITH YOUR TOKEN"; //YOUR TOKEN FOR STREAM goes HERE let yourUrl = "https://YOUR_SITE_.com/publsiher/player/?id=";

EDIT THE FOLLOWING ON PUBLISHER JS.

Open the JS/Publisher.js file. let token ="YOUR TOKEN GOES HERE";
Place the folder on your website

https://YOUR_WEB_SITE.com/publisher/publisher/player/?id=ANY_NAME

The player link will pop up or you can embed using an frame. Source will look like this. https://YOUR_WEB_SITE.com/podcaster/player/?id=ANY_NAME

Customize the publisher and player as you want. Added offline message to player and lond delay reconnect.

