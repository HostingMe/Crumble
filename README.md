# Crumble

Crumble is a lightweight, simple and fully automated cookie banner for your website. It's easy to configure and customise and with just a few lines of code you can activate and deactivate Google Analytics and Facebook Pixel.

## Installation

Before you start, you'll need to download our repository and upload the `src` directory to your `public_html` directory.

Then place the code below just above your closing `</body>` tag.
```text
<script src="/src/crumble.min.js"></script>
<script>
    crumble.start('en', {
        style: 1,
    });
</script>
```

## Customise banner

You can customise the banner and change a number of parameters. Use the tables below for details on how to add tracking codes, customise links and edit the default text, colours and more.
<br><br>
###### Tracking code

| Option        | Description                                                             | Type   | Example                            |
|---------------|-------------------------------------------------------------------------|--------|------------------------------------|
| `analytics`     | Insert your Google analytics code to allow users to opt-in to tracking. | String | `analytics :  'G-AB12CD34EF'` ,      |
| `facebookPixel` | Insert your Facebook Pixel code to allow users to opt-in to tracking.   | String | `facebookPixel : '990955817632355'`, |

<br>
###### Customise links

| Option         | Description                                                                                           | Type    | Example                                         |
|----------------|-------------------------------------------------------------------------------------------------------|---------|-------------------------------------------------|
| policyLink     | Add a link to your sites privacy policy.                                                              | String  | `policyLink :  'https://example.com/privacy' ,` |
| hideAfterClick | After a user clicks on Accept or Reject, the cookie banner will hide. The default for this is `true`. | Boolean | `hideAfterClick: true,` |


<br>
###### Extras

# Crumble

Crumble is a lightweight, simple and fully automated cookie banner for your website. It's easy to configure and customise and with just a few lines of code you can activate and deactivate Google Analytics and Facebook Pixel.

Crumble is based on <a href="https://github.com/manucaralmo/GlowCookies">GlowCookies</a>.

## Installation

Before you start, you'll need to download our repository and upload the `src` directory to your `public_html` directory.

Then place the code below just above your closing `</body>` tag.
```text
<script src="/src/crumble.min.js"></script>
<script>
    crumble.start('en', {
        style: 1,
    });
</script>
```

## Customise banner

You can customise the banner and change a number of parameters. Use the tables below for details on how to add tracking codes, customise links and edit the default text, colours and more.
<br><br>
###### Tracking code

| Option        | Description                                                             | Type   | Example                            |
|---------------|-------------------------------------------------------------------------|--------|------------------------------------|
| `analytics`     | Insert your Google analytics code to allow users to opt-in to tracking. | String | `analytics :  'G-AB12CD34EF'` ,      |
| `facebookPixel` | Insert your Facebook Pixel code to allow users to opt-in to tracking.   | String | `facebookPixel : '990955817632355'`, |

<br>
###### Customise links

| Option         | Description                                                                                           | Type    | Example                                         |
|----------------|-------------------------------------------------------------------------------------------------------|---------|-------------------------------------------------|
| policyLink     | Add a link to your sites privacy policy.                                                              | String  | `policyLink :  'https://example.com/privacy' ,` |
| hideAfterClick | After a user clicks on Accept or Reject, the cookie banner will hide. The default for this is `true`. | Boolean | `hideAfterClick: true,` |


<br>
###### Extras

| Option              	| Description                                             	| Type   	| Example                                                                	|
|---------------------	|---------------------------------------------------------	|--------	|------------------------------------------------------------------------	|
| border              	| Add or remove a border to the banner. Default: `border` 	| String 	| `border` or `none`                                                     	|
| position            	| Change the location of the banner. Default: `left`      	| String 	| `left` or `right`                                                      	|
| bannerDescription   	| Change the description text on the banner.              	| String 	| `We use cookies to ensure you get the best experience on our website.` 	|
| bannerLinkText      	| Change the text for the link.                           	| String 	| `Learn more`                                                           	|
| bannerBackground    	| Change the background of the banner.                    	| String 	| `#FAFAFA`                                                              	|
| bannerColor         	| Change the colour of the text.                          	| String 	| `#1B1B1B`                                                              	|
| bannerHeading       	| Add or change the heading of the banner.                	| String 	| `This site uses cookies`                                               	|
| acceptBtnText       	| Change the text of the accept button.                   	| String 	| `Accept cookies`                                                       	|
| acceptBtnBackground 	| Change the background colour of the accept button.      	| String 	| `#1B1B1B`                                                              	|
| acceptBtnColor      	| Change the text colour for the accept button.           	| String 	| `#FFFFFF`                                                              	|
| rejectBtnText       	| Change the text of the reject button.                   	| String 	| `Decline cookies`                                                      	|
| rejectBtnBackground 	| Change the background colour of the reject button.      	| String 	| `#FFFFFF`                                                              	|
| rejectBtnColor      	| Change the text colour for the reject button.           	| String 	| `#1B1B1B`                                                              	|

Crumble is based on <a href="https://github.com/manucaralmo/GlowCookies">GlowCookies</a>.
