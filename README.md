#### Update 4/20/19

I have not been able to address the new Apple Two Factor Authentication and this module. However, it does continue to work on my iPhone 6, iOS 11.2.6

The data no longer includes the address. However, it does include the latitude and longitude of your iPhone.
This is necessarily long for accuracy. I've tested it and I am satisfied with the results. Until I can add
this function to the module you can enter the lat and long the module gives you at this url for an address.
https://www.latlong.net/Show-Latitude-Longitude.html

The module now shows the battery power of your iPhone.

# MMM-FMI 

A MagicMirror module that beeps your iPhone and tells you its location.

## Has this ever happened to you?

How many times have you misplaced your iPhone? You know it's around there somewhere!
Do you ask someone to call your phone? What if no one is there to help you? And what if
your iPhone is on mute. That doesn't make finding it any easier. And what if you really lost your iPhone, or even worse, someone stole it?

This module will beep your iPhone even if it is on mute and will tell you it's location.

## Examples

You are presented with an iPhone image.

![](images/1.png)

When clicked, it gives you an alert window. Read the alert and click OK.

![](images/2.png)

Then you are presented with the name of your iPhone (Whatever you named it), the latitude and longitude of your phone,
and the current battery level of your phone.

![](images/5.png)

Fully customizable, Line by line. See css file.

![](images/4.png)

Click "Reset this module" and only the iPhone icon remains, ready for the next time you need to find your iPhone.

* Uses very little of your precious mirror real estate. Fits anywhere!

## Installation

* `git clone https://github.com/mykle1/MMM-FMI.git` into the `~/MagicMirror/modules` directory.

* `cd MMM-FMI`

* `npm install`

## Add to Config.js

    {
            disabled: false,
            module: 'MMM-FMI',
            header: "",                                // standard header, underlined
            position: 'bottom_center',
            config: {
                email: "Your iCloud email address",
                pass: "Your iCloud password",
                title: "",                            // Use instead of header. Not underlined! Customizable. See css file.
                maxWidth: "400px",
			}
        },

## Mad props!

This was originally cowboysdude's module/idea. For whatever reason, he lost interest in developing it.
With his permission and generosity, I completed the module and am passing it off as my own. :-)
