# Snowflake-API
Quick [Snowflake API](https://api.snowflakedev.cf:9019) wrapper for beginners.
![Snowflake-API](https://nodei.co/npm/snowflake-api.png)

# Features
- Beginner friendly
- Easy to use
- Asynchronous

# Quick Example

```js
const { API } = require("snowflake-api");
const api = new API("Super Secret API Token");

api.chatbot("Hello There").then(console.log);

api.morse("Test").then(console.log);
```
# Functions
`chatbot(message*, name[Chatbot], gender[female], userid[1])` - Returns message sent by the Chatbot *Values in [] are default values and the parameters are optional*

`token()` - Returns random Discord Token *(Note: This token is not valid)*

`meme(subreddit)` - Returns a meme from reddit *(subreddit is optional)*

`cat()` - Returns buffer for an image of cat

`dog()` - Returns buffer for an image of dog

`fox()` - Returns buffer for an image of fox

`duck()` - Returns buffer for an image of duck

`roast()` - Returns a roast in the from of a string

`pokemon(name*)` - Returns an object containing information about the Pokemon 

`morse(message*,type[encode/decode])`- Returns Morse Code encoded or decoded *(`type` specified must be either as `encode` or `decode`. Default value is `encode`)*

`registry(name*, registry*)` - Returns a package registry from the desired registry *(Registry must be one of the following: npm, deno, pypi)*

`reverse(message*)` - Returns the message reversed

`tokeninfo(token*)` - Returns the info about user from the token *(Note: token isn't stored anywhere)*

`base64(message*, type[encode/decode])` - Returns base64 encoded/decoded message *(`type` specified must be either as `encode` or `decode`, default value is `encode`)*
 
# Links
- **[Discord Support Server](https://discord.gg/QTxmjwENQx)**
- **[GitHub](https://github.com/udit2303/snowflake-api)**
