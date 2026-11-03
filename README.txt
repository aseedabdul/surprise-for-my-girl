ONE YEAR ANNIVERSARY WEBSITE
============================

HOW TO OPEN
Double-click index.html. (Fonts need internet. Voice recognition needs HTTPS, so for the
surprise section, host the folder online, see HOSTING below.)

HOW TO ADD YOUR CONTENT
Open index.html in Notepad / VS Code and find the block marked "EDIT HERE" near the bottom.

1. Photos: copy your pictures into the "images" folder, then set the paths, e.g.
   heroImg:"images/hero.jpg"
   naeImg:"images/nae.jpg"
   proposalImg:"images/proposal.png"   (blank = built-in cartoon scene)
   memories: img:"images/m1.jpg" ... for each of the 10 memories, plus title:"Your text"
2. Poems: replace the text in poems:[ ... ] (POEM_01 to POEM_06).
3. Special message: edit  special:"..."
4. QR code: save your QR as images/qr.png, then set  qrImg:"images/qr.png"
   and  qrUrl:"https://your-link"  (the button for opening it on the same phone).
5. Optional voice recording: put an mp3 in "audio" and set  voiceAudio:"audio/voice.mp3"
6. Optional own character picture: mascotImg:"images/mascot.png"

HOSTING (free, private link)
Drag this whole folder onto netlify.com/drop or upload it to Vercel. Share the link only
with her. The page is set to noindex so search engines skip it.

VOICE NOTES
Works best in Chrome or Edge (Android and desktop). Unreliable on iPhone Safari, not
supported in Firefox. If the microphone is blocked, a tap-to-count button appears.
