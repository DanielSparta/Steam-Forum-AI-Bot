# Steam-Forum-AI-Bot
I researched Steam's protocols to create an API for an AI bot that logs into accounts, detects the email code that was sent, and then talks with other players.
This bot talks with other players, saying things like "There are no cheaters in CS2", "VAC is a built-in feature that is well embedded within the game's code", etc.

To use this bot, you simply need to put the username and password in a file called config.steam. If it's an email from https://www.emailnator.com/, the code can detect the email verification code by itself, but you'll need to make a small change in the code so that the GmailNator class is used (the code already exists but isn't enabled by default). If you don't use Emailnator (for example, your real Gmail account), you'll need to validate the email code yourself.

# Fun facts
1. Some angry person tried to sue Valve because of this bot.
2. As part of the research I did for this project, I discovered some security vulnerabilities. I chained them and developed a vulnerability chain for Steam Client 1-Click RCE. I reported it (along with additional vulnerabilities) to Valve's bug bounty program on HackerOne, and they fixed most of these vulnerabilities.

The vulnerabilities they didn't fix, on the other hand, are currently of informative severity, but they still allow things like performing remote payment-related actions on other players' accounts, XSS-to-RCE chains caused by incomplete fixes to my earlier vulnerabilities, performing actions on partner organizations after you've been removed from them, and more. There are many of these, but Valve refuses to even listen or fix them. I find it concerning that Valve doesn't care much about user security, or about any vulnerability that doesn't have a direct impact on the business itself. I don't currently want to disclose these vulnerabilities, because they would be exploited by attackers. **While I love Valve for its history, I can't not hate them, knowing which vulnerabilities they're ignoring.**

# Setup Video Tutorial:
https://www.youtube.com/watch?v=FuJ86rf4pkw

![image](https://github.com/user-attachments/assets/eb7a2566-e4b0-455d-a7ea-0bba861e2742)

![image](https://github.com/user-attachments/assets/8ddaf98a-0876-42b6-a053-73434c8c4690)


![image](https://github.com/user-attachments/assets/a8f6f9d4-e049-4e00-a1b8-abb281d0ba5b)


![image](https://github.com/user-attachments/assets/0cd97e0c-a5ac-4a78-85b8-29a1a28f6e97)

![image](https://github.com/user-attachments/assets/60eaa69b-b62a-4014-9fe4-25cb63ebc5ac)


# A lot of Steam points
Those players don't know they're arguing with an AI bot.

![image](https://github.com/user-attachments/assets/0923ab55-0187-4376-b676-b79b7825f296)
