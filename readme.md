# Delta Defense Web Page Mockup  
by Katherine Hambley  
## Overview  
Some things that jumped out at me right away when I started:  
(These are the questions I would ask the designer for clarification...)  
- No footer on either one of the mockups? Was that left out intentionally?  
- No header on the mobile version of the mockups? Was that left out intentionally?  
- The “Here to Help 24/7” white bar under the header is a screenshot, so I wasn’t able to get the text color and size from the mockup. In a real world scenario, I would ask the designer for specifics as far as the font size, color and text position.  
- I wasn't sure what was referred to as "uranus" on the XD design mockup, with the blue circle with a white number 4 in the center, so I just replicated the circle in CSS.
- For the "USCCA COMMUNITY & CONNECTION" headline text, I see that it is an image in the mockup. I would prefer to use text instead of an image. Screen readers (accessibility) have a hard time reading the text and so do search engines. Also, if you ever want to localize your page, it's nearly impossible if the text is displayed as an image. If a real world project, I would encourage the designer to provide font family and size rather than an image to stick with best practices.
- On the mockup, in the "Online Community" box on the left on desktop, a period is missing at the end of the sentence.  
- On the mockup, in the "Expert Customer Engagement Team" box on the right on desktop, a period is missing at the end of the sentence.
- I wasn't sure if the reordering of the panels was intentional, I'd ask the designer to clarify that if it is a real project. There was no mention of whether the order of the panels mattered on desktop vs. mobile. Typically, a designer will make a comment and number the boxes to explicitly call out the order on each mockup. If it does matter, I'd probably put the panels in rows and col divs so I can reorder the panels at the correct breakpoint.
- The other breakpoints didn't get much attention in the interests of time. I worked on and tweaked the desktop (xl) and mobile phone (sm) breakpoints only that were in the mockup.
- I tested the page in Microsoft Edge, Apple Safari, Google Chrome, and Firefox. As well as on iPhone 13 mobile phone device.


## Bootstrap 4 vs. 5  
I decided to use Bootstrap 4 vs. Bootstrap 5 version. Reasons below:  
- Bootstrap 5 was released May of last year (2021). It's still under heavy development and not as mature as Bootstrap 4. I tend to be fairly slow to adopt new versions of web frameworks for professional projects until they have had time to work out the bugs and fix the edge cases. It also allows for the community to develop and embrace the new version, so there is more documentation available if I run into issues.  
- Bootstrap 5 doesn't support IE browsers. I wasn't given a targeted audience of users, or analytics on what the targeted users use for their browser, so I went with the broadest range of users and browsers to support. Bootstrap 4 supports later versions of IE out of the box. Bootstrap 5 does not. The downside is version 4 relies heavily on jQuery but it will be easy enough to upgrade to 5 when jQuery is EOL.






