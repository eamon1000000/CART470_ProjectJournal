# Week 9

## Second round of feedback on pull requests

This week Gabriel left two more comments on my first pull request. It's still the only one he's looked at so far, so things are moving a bit slower than I anticipated, or understood was necessary, but the feedback has been useful.

His first comment was about the LFO on the filters. In the score file, it wasn't clear that the LFO was changing the frequency, so I moved it under the key for frequency itself, the way he suggested to me. His second question was why the score has both an `effects` key and an `effectEvents` key in the score. I kept them separate because it makes more sense to me that way, where the effects one sets up each group's effect chain and the effectEvents programs the changes it over time, so I added a line to the read me to make it understood, but also shared my openness to change it if he wants it to be different.

While going through his comments, I realized that it was difficult to actually create an effect change as a user in our current form. The dropdown was empty unless you had already added effects further up the page,which  I reworked so you pick an effect and then one of its settings, and it shows what value you're changing from in the initial setup. If there are no effects yet, it tells you to add them above.

### Reworked effect changes area in the score editor
<img width="1020" height="1146" alt="Screenshot 2026-11-17 212855" src="https://github.com/user-attachments/assets/dd2e98f0-c098-45f4-9309-1685ab234f91" />

I pushed everything and emailed Gabriel explaining the changes and my reasoning, however I'm still feeling a bit out of the loop on what he wants. 

As we move into the last three weeks of this project, I think it will be important to maintainn an open line of communication with him, if he wants this project finalized. To clarify exact details, I will try to meet with him during his sound class as well next week to udnerstand the more precise use cases of the software. 

Now I'm switching back to our own version of the project and porting some of his features into our version.

The live timeline and playback preview he has is a really useful feature, so I'm porting it into our JSON form. We already have a basic preview, but seeing the whole score laid out visually, and hearing the drift and effects before a performance, would make it a lot easier for students to write their pieces.

## Next Step
[Week 10: ?](https://github.com/eamon1000000/CART470_ProjectJournal/tree/Week-10)

## Table of Contents
[Week 2: Project Brief](https://github.com/eamon1000000/CART470_ProjectJournal/tree/Week-2)

[Week 3: Meeting our Client](https://github.com/eamon1000000/CART470_ProjectJournal/tree/Week-3)

[Week 4: Continued client meetings and development](https://github.com/eamon1000000/CART470_ProjectJournal/tree/Week-4)

[Week 5: Making a working example](https://github.com/eamon1000000/CART470_ProjectJournal/tree/Week-5)

[Week 6: Tying our efforts together](https://github.com/eamon1000000/CART470_ProjectJournal/tree/Week-6)

[Week 7: Pivoting for the client](https://github.com/eamon1000000/CART470_ProjectJournal/tree/Week-7)

[Week 8: Polishing and handing it over](https://github.com/eamon1000000/CART470_ProjectJournal/tree/Week-8)

[Week 9: Second round of feedback on pull requests](https://github.com/eamon1000000/CART470_ProjectJournal/tree/Week-9)
