# DSA-Check-if-the-Sentence-Is-Pangram
A pangram is a sentence where every letter of the English alphabet appears at least once.
Given a string sentence containing only lowercase English letters, return true if sentence is a pangram, or false otherwise.
```
Input: sentence = "thequickbrownfoxjumpsoverthelazydog"
Output: true
Explanation: sentence contains at least one of every letter of the English alphabet.
```
```
class Solution:
    def checkIfPangram(self, sentence: str) -> bool:
        sentence=set(sentence)
        if len(sentence)==26:
            return True
        else:
            return False
    
```
