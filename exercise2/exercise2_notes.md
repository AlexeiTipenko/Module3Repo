# Notes and observations for exercise 2

---

* I did not know that such a powerful tool (open refine) existed before this exercise.

* It is really efficient at merging similar words. I can imagine how difficult it would be to do this all by hand.

* Since I've started to merge words together, I've noticed that my sender and receiver cluster numbersa little bit higher than what is estimated in the exercise instructions.

* When I first started merging, I was only able to find fix about 15-20 conflicts for each of the 2 columns. Then I dicovered that changing the radius and character block number for some of the dropdown selections showed me more conflicts that I was able to merge.

* After fixing about 25-35 conflicts for each column, I decided to quickly skim the data manually to see if I could fix up some obvious errors that open refine could not reccomend to me. Words like "Alc6e" I left alone. However, unclosed brackets and obvious spelling errors that caught my attention were fixed.

---

* Again, It's really nice to have an open source tool like Palladio available.
* I've noticed that there isn't much I can visualize with the imported csv file other than to graph the results.
* By graphing the sender to the receiver (source to target), I found gained some interesting insights about the data:

1. Some names came up a lot more than others, and these people acted as both         senders and receivers (you can see this by highlighting first the sender then the receiver and seeing no significant changes)

2. The names of the people who only sent out a few (probably just 1) letter out to             someone appeared as part of the outer cluster of the graph.

3. Open refine was not able to fix all the mistakes, some weird sentences appeared instead of people's names such as "A Friend of Treat in Mexico". Further cleaning may have been needed to get more consistent results.
