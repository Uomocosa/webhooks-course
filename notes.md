[![Learn to code with TwilioQuest](https://img.shields.io/static/v1?label=TwilioQuest&message=Learn%20to%20code%21&color=F22F46&labelColor=1f243c&style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAIAAAACACAMAAAD04JH5AAAASFBMVEUAAAAZGRkcHBwjIyMoKCgAAABgYGBoaGiAgICMjIyzs7PJycnMzMzNzc3UoBfd3d3m5ubqrhfrMEDu7u739/f4vSb/3AD///9tbdyEAAAABXRSTlMAAAAAAMJrBrEAAAKoSURBVHgB7ZrRcuI6EESdyxXGYoNFvMD//+l2bSszRgyUYpFAsXOeiJGmj4NkuWx1Qeh+Ekl9DgEXOBwOx+Px5xyQhDykfgq4wG63MxxaR4ddIkg6Ul3g84vCIcjPBA5gmUMeXESrlukuoK33+33uID8TWeLAdOWsKpJYzwVMB7bOzYSGOciyUlXSn0/ABXTosJ1M1SbypZ4O4MbZuIDMU02PMbauhhHMHXbmebmALIiEbbbbbUrpF1gwE9kFfRNAJaP+FQEXCCTGyJ4ngDrjOFo3jEL5JdqjF/pueR4cCeCGgAtwmuRS6gDwaRiGvu+DMFwSBLTE3+jF8JyuV1okPZ+AC4hDFhCHyHQjdjPHUKFDlHSJkHQXMB3KpSwXNGJPcwwTdZiXlRN0gSp0zpWxNtM0beYE0nRH6QIbO7rawwXaBYz0j78gxjokDuv12gVeUuBD0MDi0OQCLvDaAho4juP1Q/jkAncXqIcCfd+7gAu4QLMACCLxpRsSuQh0igu0C9Svhi7weAGZg50L3IE3cai4IfkNZAC8dfdhsUD3CgKBVC9JE5ABAFzg4QL/taYPAAWrHdYcgfLaIgAXWJ7OV38n1LEF8tt2TH29E+QAoDoO5Ve/LtCQDmKM9kPbvCEBApK+IXzbcSJ0cIGF6e8gpcRhUDogWZ8JnaWjPXc/fNnBBUKRngiHgTUSivSzDRDgHZQOLvBQgf8rRt+VdBUUhwkU6VpJ+xcOwQUqZr+mR0kvBUgv6cB4+37hQAkXqE8PwGisGhJtN4xAHMzrsgvI7rccXqSvKh6jltGlrOHA3Xk1At3LC4QiPdX9/0ndHpGVvTjR4bZA1ypAKgVcwE5vx74ulwIugDt8e/X7JgfkucBMIAr26ndnB4UCLnDOqvteQsHlgX9N4A+c4cW3DXSPbwAAAABJRU5ErkJggg==)](https://twilio.com/quest?utm_source=gh-badge&utm_medium=referral&utm_campaign=webhooks)

# Understanding Webhooks

## Unit 1  - Integration

In this unit we will focus on combining applications together. We'll do this by handling events triggered by applications.

### Video 1 - Welcome

#### Prerequisites

* 🎥[APIs for Beginners on freeCodeCamp](https://www.youtube.com/watch?v=GZvSYJDk-us&feature=youtu.be)

#### 📚 Learn more

* [freeCodeCamp.org](https://freecodecamp.org)

### Video 2 - Defining Events, Handlers, and Hooks

* [Web Events](https://developer.mozilla.org/en-US/docs/Web/Events)

#### 📚 Learn more

* [Event Driven Programming](https://wiki.c2.com/?EventDrivenProgramming)

### Video 3 - Lightbulb moment

#### 💡 Ideas

* Think about the weather. Do you want to use the light if it gets rainy/snowy/chilly/hot?
* What about your location? Want to trigger something when you leave a certain area at a certain time?
* Think about notifications you get on your phone. Would those be cool to light up the weird dog lamp thing?
* What about controlling your lights based on a text message?

#### 📚 Learn more

* The dog lamp [LIFX lightbulb](https://www.lifx.com/collections/lamps-and-pendants/products/lifx-color-a19)

### Video 4 - Finding Inspiration

## Unit 2 - Capturing Data from a Webhook

In this unit we'll take a look at a specific Webhook implementations [GitHub](https://github.com) and [Discord](https://discord.com).

### Video 1 - Diving into Webhooks

* [First blog post about "Web hooks" - Wayback machine](https://web.archive.org/web/20180630220036/http://progrium.com/blog/2007/05/03/web-hooks-to-revolutionize-the-web/)
* [📹 Web Hooks and the Programmable World of Tomorrow- 2009 talk about Webhooks @ Google](https://www.youtube.com/watch?v=Fw8EPrIjCOc)

### Video 2 - Explore the Request

* [Beeceptor](https://beeceptor.com)
* [- Uomo]
Using beeceptor lets u create a "moking" url for sending webhook post to it after creating an url with beeceptor (~for exemple: https://porva1.free.beeceptor.com) u can use it as an endpoint to handle the weebhook.
In the course for testing it we go from github to settings>>Webhook and then create a new webhook, in the url space we use the beeceptor that we created, than check "Let me select individual events" and select the event: "Star" (adding or remove a star from this repo).
When we star this repo we should see a change at the url created with beeceptor

#### 📚 Learn more
* [🎮 TwilioQuest - The Flame of Open Source - Learn to use GitHub](https://www.twilio.com/quest/learn/open-source?utm_source=freecodecamp&utm_medium=github&utm_campaign=webhooks)

### Video 3 - Using the Data

* [Best Developer Communities to be a part of in 2020 - freeCodeCamp.org](https://www.freecodecamp.org/news/best-developer-communities-to-be-part-of-in-2020/)

### Video 4 - Developing Locally

⚠️ I made a mistake! I cloned in my `~/Code` directory because I forgot to `cd courses`.

#### Installations

* [14 ways to open Command Prompt in Windows 10](https://www.digitalcitizen.life/open-cmd/)
* [Install Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* [Install Node](https://nodejs.org/en/download/)
* [Install npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
* [Install Visual Studio Code](https://code.visualstudio.com/download)
* [Optional - Connect GitHub with ssh](https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/connecting-to-github-with-ssh)

* [- Uomo]
* How to copy and open any code from "GitHub" to "Visual Studio Core" using "Git":
* 0. From GitHub go to "Code" and copy the url
* 1. Open "Command Prompt"
* 2. Go to the folder u want to open (~ ex.: C:\Users\Uomocosa\Code\Webhooks) using the command "cd" in the command prompt, it lets u open the folder (es.: starting from C:\Users\Uomocosa; type "cd Code" then enter, then "cd Webhooks")
* 3. Type "git clone " and paste the URL copied from github then press Enter
* 4. Type "code ." then press enter

* [- Uomo]
* How to start your local host
* 1. In the command promt or the terminal on "Visual Studio Code" go to the folder u want to open in your local host (~es.: C:\Users\Uomocosa\Code\Webhooks\webhooks-course\code\express-discorder), u can move from folder to folder in the terminal using the "cd" command.
* 2. type "npm install" then enter
* 3. type "npm start" then enter
* You have now created your local host at: http://localhost:3000
* (N.B.: 3000 is the port of your local host)

### Video 5 - Opening a Tunnel

#### Installations

* [Install ngrok](https://ngrok.com)
* [Install ngrok to your path - Stack Overflow](https://stackoverflow.com/questions/30188582/ngrok-command-not-found)
* [Install nodemon](https://www.npmjs.com/package/nodemon):

```bash
npm install -g nodemon
```
* [- Uomo]
* ngrok creates a tunnel form your local host to the internet allawing u to use the url given by ngrok as an endpoint for your webhook
* for doing so u have to (after installing ngrok and opening you local host) type in your terminal:
```bash
ngrok http 3000
```

#### 📚 Learn more

* 🎥 [The making of ngrok - Alan Shreve (ngrok)](https://www.youtube.com/watch?v=F_xNOVY96Ng)

### Video 6 - Serverless

* [Netlify](https://www.netlify.com)

```bash
npm install netlify-cli -g
```
* [- Uomo]
* netlify allows you to have a servless function for free (under certain parameters) it creates an endpoint (same as ngrok) but this time it actualy is on the internet, u might think it as a step above ngrok, with some differences.
* To upload a serveless function from your pc:
* 1. In the command promt or the terminal on "Visual Studio Code" go to the folder u want to open in your local host (~es.: C:\Users\Uomocosa\Code\Webhooks\webhooks-course\code\netlify-discorder), u can move from folder to folder in the terminal using the "cd" command.
* 2. npm install
* 2.5. if u are not logged in in netlify: netlify login
* 3. netlify deploy --prod
* 4. then select + Create & configure new site
* 5. then select the team in wich u want to save the function
* 6. then enter the name of the site u want to create
* 7. then select the directory u want to publish (pressing enter selects the current directory)

#### 📚 Learn more

* [Making asynchronous programming easier with async and await
](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous/Async_await)
* [Netlify Dev - Local server](https://www.netlify.com/products/dev/)
* [Cloud Computing Providers - GitHub](https://github.com/tmrts/awesome-cloud-computing)

#### 🖊 Correction

📓 I figured out what my problem was! After you change environment variables in Netlify, you need to re-deploy. That's the reason it worked once I re-deployed it. I decided to keep the bugs in there so you know that **we all make mistakes**. Also it should give you some first hand knowledge of how to debug a webhook.

I hope you enjoy the lemonade made from the lemons of that bit 🍋s.

### Unit 3 - Hooking it altogether

In this unit we'll build an entire application that leans almost entirely on the concept of Webhooks. We'll build an idea capturing hotline that transcribes the ideas and then sends you a text message.

### Video 1 - Introducing the projects

### Video 2 - Text Affirmation

* [Twilio Signup](https://www.twilio.com/referral/d4X15O)
* [How to use your free trial account - Twilio Docs](https://www.twilio.com/docs/usage/tutorials/how-to-use-your-free-trial-account)

The following [TwiML](https://twilio.com/docs/sms/twiml) will send a text message when set up to handle incoming messages.

```xml
<Response>
    <Message>You got this!💪</Message>
</Response>
```

This is using a Webhook. When the message comes in, control is passed to your application (it just happens to be in a TwiML Bin), and you return these instructions.

#### 📚 Learn more

* [`<Message>` - Twilio Docs](https://www.twilio.com/docs/sms/twiml/message)
* [TwiML Bins](https://www.twilio.com/docs/runtime/tutorials/twiml-bins)

### Video 3 - Setting up the flow

#### 📚 Learn more

* [`<Say>` - Twilio docs](https://www.twilio.com/docs/voice/twiml/say)
* [Polly Neural voices - Amazon docs](https://docs.aws.amazon.com/polly/latest/dg/NTTS-main.html)
* [Twilio Studio](https://twilio.com/studio)

### Video 4 - Handle things locally

* [Twilio CLI Quickstart](https://www.twilio.com/docs/twilio-cli/quickstart)

```bash
npm install twilio-cli -g
```

Optionally on a Mac, you could use [Homebrew](https://brew.sh)

```bash
brew tap twilio/brew && brew install twilio
```

Install the [Serverless Toolkit](https://www.twilio.com/docs/labs/serverless-toolkit) plugin:

```bash
twilio plugins:install @twilio-labs/plugin-serverless
```

Serverless Function boilerplate:

```javascript
exports.handler = (context, event, callback) => {
  callback(null, "Hi mom!");
};
```

Start your local development server

```bash
twilio serverless:start
```

### Video 5 - Deploying your serverless function

```bash
twilio serverless:deploy
```

### Video 6 - That’s a Wrap

* 🎮 [TwilioQuest - Learn to code and save the cloud](https://www.twilio.com/quest?utm_source=freecodecamp&utm_medium=github&utm_campaign=webhooks)
