# Week 3

## Meeting our client

This week we met our client Gabriel twice and got a better understanding of his expectations and expertise for the project. I missed the second meeting, but caught up through the notes my teammates left in our google doc.

He clarified the details about how we will be receiving the audio, and how we should structure the app for his students. I understand now that he wants us to essentially create an open-source tool that his students can fork from our Github repo and adjust to their needs, adding their own sound files and writing/customizing a JSON 'score' to program the playback of the audio files.

Jessica started a simple demo that plays audio through the server and I built on it by adding a 'Phone' class to represent each connected device. When a device connects now, the server creates a 'Phone' and gives it an ID, counting up from 0 each time the server starts. It then places the phone in a group by dividing the ID by the number of groups and taking the remainder (modulo). Each Phone records whether it's currently playing, and phones are removed when they disconnect.

It works simply across 2 locally hosted browser pages, which is a good start. We will continue to work on it this week according to our timeline.

We also all worked on the [Living Learning Contract](https://github.com/eamon1000000/CART470_ProjectJournal/tree/Living-Learning-Contract) and aligned it with the new understanding of the project that we got from Gabriel this week

## Next Step
[Week 4: ?](https://github.com/eamon1000000/CART470_ProjectJournal/tree/Week-4)


## Table of Contents
[Week 2: Project Brief](https://github.com/eamon1000000/CART470_ProjectJournal/tree/Week-2)
[Week 3: Meeting our Client](https://github.com/eamon1000000/CART470_ProjectJournal/tree/Week-3)
[Week 4: ?](https://github.com/eamon1000000/CART470_ProjectJournal/tree/Week-4)

