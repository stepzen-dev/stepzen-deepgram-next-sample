This repository is a sample of an app made with StepZen, Deepgram, and Next.js. 

To take a closer look at my project on your local machine, `git clone https://github.com/Cerchie/fun-with-deepgram-and-next && cd fun-with-deepgram-and-next && npm install && npm run dev`. (You'll need [npm](https://www.npmjs.com/) installed.)
You'll also need to make a file in your root directory called `env.local` and put your Deepgram apikey in it like so: `DEEPGRAM_APIKEY=your_apikey_here`

You can learn more about the inner workings by consulting the [Next](https://nextjs.org/docs), [StepZen](https://stepzen.com/docs) and [Deepgram](https://developers.deepgram.com/) documentation.

Right now the calls are made to one English audiofile hosted by Deepgram, and one French audiofile [hosted elsewhere](https://www.lightbulblanguages.co.uk/resources-sound-files.htm#age), to experiment with multiple language support options offered by the `language` parameter. Then the transcript is rendered to the home page. 
