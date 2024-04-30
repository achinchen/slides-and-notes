## Knowledge - Clean Code - 原則在遵守時候的 N 不 M 沒有

## Before Diving

### Why do we need the clean code?
- Increase the jobs for the future ME/US.
  - isolate feature side effects.

### Why do you want to know what the clean code is?
- readability
- maintability
- testability
- without unexpectedly side effect.
- extendability
- * single responsibility


## Let's try to definite it togather
- Principals from my own experiences.
	- Don't make the person reading your code feel confused.
	- Assign a responsibility to a function and stick to it.
	- The sooner code is written, the more likely it is to be incorrect; the sooner code is written, the harder it is to maintain.
- Make it work and make it perfect.
- N + M -> You cannot know what it wants to do in a sec
  - if + elseif + else
	- naming
	- duplication code in the small block
	- XSS - security issue.
	- responsibility in one function
	- Inconsistent variables naming
	- dead code - 沒有刪掉不需要的 code 或是註解掉
	- cross folder import or reference
	- A && B || C ? D : E

## Conclusion
	- If we don't know the purpose of the clean code then we were never getting to know what we need to do these things at all. Which means we cannot owe the legacy consciously.
	> 如果你愛一個人，一定要告訴他，不是為了要他報答，而是讓他在以後黑暗的日子裡，否定自己的時候，想起世界上還有人這麼愛他，他並非一無是處。   
