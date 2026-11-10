# Week 8

## Continuing to polish, and working with Gabriel as he introduces the software to his students

This week was primarily about debugging the features I ported into Gabriel's version last week, getting them ready for him to use, then creating proper pull requests for his repo.

Starting with the score editor, some of the styling had broken during the port, so I went back to how we had done things in our version and fixed it. I also changed the layout a bit so that the score preview and playback now sit below the form instead of beside it, and I made the list of uploaded audio files much more compact, because it was taking up way too much space and getting in the way on the form. I also fixed a small issue in the preview timeline where the titles of sounds were overlapping when a group played more than one sound at the same time; they now stack on top of eachother so you can see the names of both files clearly.

Testing with phones on his version (where he uses mqtt as opposed to our server based setup) has been a struggle because of the university wifi, which blocks the phones from connecting to a laptop's IP adress (i think?). To get around it, Gabriel suggested I run a local server with http-server and open a tunnel with cloudflared, which gives a public link the phones can open. I added these steps to the his documentation.

I then made a separate branch to remove things that I thought weren't needed. I removed his old landing page and the "Free" mode on his conductor page, so it is now only about playing from a score, much more similar to our version, with his framework. I think this will keep it a lot simpler for his students, but ultimately it's up to him to decide what features he wants to keep. 

### Score editor with the new layout
<img width="1684" height="3794" alt="adapters-clothing-controlling-reporter trycloudflare com_ensemble_editor html_score=0 (1)" src="https://github.com/user-attachments/assets/4bc17238-4b1e-49e5-9f81-89f20bb25f75" />


Once it all worked properly, I opened three pull requests on Gabriel's repository, one for each stage of the work (effects, score editor and retrieving score from GitHub, and the cleanup/debloated version), so he could review and merge them one at a time. I also emailed him and met with him to explain what each one does and iron out some issues relating to the pan effect.

after all this, I tested everything again with phones, and score building workflow.

# Next steps
He is hoping to demo this new version with effects and score writing next week, so hopefully I will be able to sit in on that. This week however, I hope to turn my attention back to our version, and continue to make a product we are all proud of


## Next Step
[Week 9: ?](https://github.com/eamon1000000/CART470_ProjectJournal/tree/Week-9)

## Table of Contents
[Week 2: Project Brief](https://github.com/eamon1000000/CART470_ProjectJournal/tree/Week-2)

[Week 3: Meeting our Client](https://github.com/eamon1000000/CART470_ProjectJournal/tree/Week-3)

[Week 4: Continued client meetings and development](https://github.com/eamon1000000/CART470_ProjectJournal/tree/Week-4)

[Week 5: Making a working example](https://github.com/eamon1000000/CART470_ProjectJournal/tree/Week-5)

[Week 6: Tying our efforts together](https://github.com/eamon1000000/CART470_ProjectJournal/tree/Week-6)

[Week 7: Pivoting for the client](https://github.com/eamon1000000/CART470_ProjectJournal/tree/Week-7)

[Week 8: Continuing to polish, and working with Gabriel as he introduces the software to his students](https://github.com/eamon1000000/CART470_ProjectJournal/tree/Week-8)
