BBStylish is a stylesheet for BBEdit’s Preview window that offers attractive defaults, but can be customised with little to no knowledge of <abbr>CSS</abbr>.

[Download BBStylish (Version 2)][bbs-zip]

<img src="https://nostodnayr.net/misc/2019/10/bbstylish-sf-light.png"
     alt="Screenshot of this article previewed using the BBStylish stylesheet in the ‘Preview in BBEdit’ window."
     style="width: 40%;">

[Read the BBStylish introduction post][toab]

[bbs-zip]: https://nostodnayr.net/projects/downloads/bbstylish-latest.zip
[toab]: https://nostodnayr.net/2019/10/styled-to-a-b "Styled to a ‘B’ · nostodnayr.net"



How BBStylish works
-------------------

You can customise BBStylish to better suit your preferences. Out of necessity this requires some precision, but I’ve tried to make it approachable, even if you’re not familiar or comfortable with <abbr>CSS</abbr>. Explanations and examples are given for each of the ‘settings’.

The setting (variable) is preceded by two hyphens and ends with a colon, like so:

	--text-zoom:

Your setting goes after the colon, followed by a *semicolon*. Thus a full setting line looks like this:

	--text-zoom:  120;

***Important:*** This bears repeating – the line must end with a semicolon.

Apart from that, the other important note is that spaces and tabs are ignored, except between quotation marks.



How to use BBStylish
--------------------

The `DefaultCSS_Markdown.css` file must be placed in the *Preview CSS* folder of BBEdit’s Application Support folder. The easiest way to open that folder is from the menu bar: choose **BBEdit › Folders › Preview CSS** and drag the file to the folder.

Then, *write*.

When you’re ready, open the Preview window: **Markup › Preview in BBEdit** (⌃⌘P)

***Note:*** If the name of the file is left unmodified, BBStylish will be used as the default stylesheet when you preview any Markdown file. If you don’t want that, rename the file and ensure that the `.css` extension is maintained. When you want to use it, choose the file from the ‘CSS’ pop-up menu in the Preview window.



Customising BBStylish
---------------------

All the instructions for editing the settings for BBStylish are included in the file. And obviously the best way to edit the file is *in BBEdit*.

You can open the file directly from the Preview window, hold down the Option (⌥) key as you choose the file from the CSS pop-up menu. When you save the file, the changes are reflected immediately.



Dark Mode and BBStylish
-----------------------

When your system appearance, or the BBEdit appearance, is set to dark, BBStylish will use the `--dark-mode-` colours specified in the file. Enjoy.

If you always want the light or dark version, despite the appearance, duplicate the desired colour values to be the same for both sets.



Font choices
------------

Every Mac comes with some fantastic typefaces you could use for BBStylish. I chose the system *San Francisco* font as the default because it pretty much always looks good. *Georgia* can also look nice:

<img src="https://nostodnayr.net/misc/2019/10/bbstylish-georgia-dark.png"
     alt="Screenshot of this article previewed using the BBStylish stylesheet, this time using the New York Small font."
     style="width: 30%;">

Excellent choices abound – Gill Sans and Hoefler Text, for example – try different ones, with different text zoom factors and line heights, to find your favourite.

Fortunately BBEdit can, unlike Safari, still access your locally-installed fonts so anything you’ve got installed is also fair game.


* * * *


If you have any questions, comments or suggestions about BBStylish, please email me at <rd@nostodnayr.net>.
