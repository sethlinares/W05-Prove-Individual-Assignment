**CSE 212 – Programming with Data Structures**

**W05 Prove – Response Document**

------------------------------------------

_It is a violation of BYU-Idaho Honor Code to post or share this document with others or to post it online.  Storage into a personal and private repository (e.g. private GitHub repository, unshared Google Drive folder) is acceptable._

------------------------------------------

**Question 1:**  From Part 1, how did you answer the interview question for the Set Operations problem (should be no more than 30 seconds if spoken aloud)?

In the Set Operations problem, I implemented the Intersection and Union operations using a HashSet. For Intersection, I looped through one of the sets and checked if each element was present in the second set, adding it to the resulting set if it was. For Union, I added all elements from the second set to the first one, which automatically handles duplicates due to the properties of a HashSet. This approach ensures time complexity of O(n) for both operations, as each element in the sets is processed exactly once.

**Question 2:**  From Part 2, how did you answer the interview question for the Find Pairs problem (should be no more than 30 seconds if spoken aloud)?

In the Display Pairs problem, I also leveraged the HashSet data structure. I iterated through the given words, adding each to the HashSet. In the same loop, I checked if the reversed pair of the word was already in the HashSet and if so, printed the pair. This way, each word and its potential pair are processed only once, achieving O(n) time complexity. A special check was added to ensure that words with duplicate characters like 'aa' don't create false pairs.

------------------------------------------

_Remember:  Make sure all of your changes are committed and pushed to the `main` branch of your_ **prove-05-[username]** _repository_

_Also, submit this document and a link to your repository in I-Learn_
