# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
- List at least two concrete bugs you noticed at the start  
  (for example: "the hints were backwards").

--- The first glitch I found was putting one and it told me to go lower even if the interval is from 1 - 100. The second glitch I found is that the guesses are not limited to 1 - 100 and you could any number and no matter what it will always say go lower. The third glitch I found was that starting a new game didnt change anything other than the number to guess. Then once the new is game "started" it does not check the new answers only gets rid of attempts.

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).

--- I used Claude code on this Project. The suggestion to make sure the guess and secret were parsed as intergers worked well and I played the game to see if it would return the correct string of "go lower" and "go higher". But, and incorrect idea that was placed by an AI was the change of the comparison to see which string to return and I verified by running the game again.

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

---I determined if a bug was actually fixed by running the game myself manually. It showed that the opposite was being returned for the strings. AI did help design the fix by parsing the variables correctly and make sure all variables were reset when a new game was started.

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.
