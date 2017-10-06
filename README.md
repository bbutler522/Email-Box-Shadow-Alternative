# Email-Box-Shadow-Alternative
A straightforward and seemingly cross-browser solution to add a psuedo box-shadow to HTML Emails. Getting email templates working stylistically cross-device/browser can be a challenge, so this is a solution to one type of common CSS3 style that won't work on most clients.
https://codepen.io/brennanrome/pen/QqQqqa

## Instructions
1. Create the desired box-shadow in photoshop including transparency and save it as a png.
2. Upload your file to your hosting and include the path as the background in the table cell.
3. Set the height to match your png height to avoid vertical repeating tiles.
4. Set the bgcolor to match the background color that the shadow is to fade into.

`<td bgcolor="#363639" height="8" background="header-shadow.png"></td>`

## Additional Requirements
- The <td> will need to have no margin, padding, or border between the two elements that you want to connect.
- The box-shadow will tile horizontally by default, but can be constrained if desired.

## Compatability
Tested in Litmus and working on
- G Suite (Chrome, Explorer, Firefox)
- Gmail (Chrome, Explorer, Firefox)
- Inbox by Gmail (Chrome, Explorer, Firefox)
- Apple Mail 10, 9
- Outlook (OSX)
- Thunderbird 52 (Windows 7)
- Android 4.4
- Gmail App (Android 6)
- iPad (Retina), iPad Mini (iOS 10.3.2)
- iPhone iOS 7, 8, 9
- AOL Mail

Not working on
- Outlook (Windows 7)
- Windows 10 Mail

## Feel free to add additional compatability notes, or make suggestions to improve usability or compatability!
