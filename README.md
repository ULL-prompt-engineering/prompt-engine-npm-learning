## Install dependencies

```
npm i
```

## Execution ChatExample.js

```
prompt-engine-learning git:(main) node ChatExample.js 
PROMPT

I want to speak with a bot which replies in under 20 words each time

USER: Hi
BOT: I'm a chatbot. I can chat with you about anything you'd like.

USER: Can you help me with the size of the universe?
BOT: Sure. The universe is estimated to be around 93 billion light years in diameter.

Forget the earlier conversation and start afresh

USER: What is the maximum speed an SUV from a performance brand can achieve?
BOT: Some performance SUVs can reach speeds over 150mph.

USER: Can some cars reach higher speeds than that?

PROMPT LENGTH: 523
```

## Execution OpenAIExample.js

```
➜  prompt-engine-learning git:(main) node OpenAIExample.js               
Enter your command: What's the minimum of 4 and 9?
We have built the prompt:
/* Natural Language Commands to Math Code */

/* what's 10 plus 18 */
console.log(10 + 18)

/* what's 10 times 18 */
console.log(10 * 18)

/* What's the minimum of 4 and 9? */

console.log(Math.min(4, 9))
```