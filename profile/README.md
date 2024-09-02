![Whiskey logo](https://images.ctfassets.net/zh68lrw89i3n/4t5mMRScXQuGf7EnnqNkwu/e19a6d0c943225c1ec1c13059a754515/Original_Logo.png)

# The Whiskey Platform

Hi, I'm [Matt Wyskiel](https://github.com/mattwyskiel) and the Whiskey Platform is my personal, mostly-open-source effort to apply my ethos--of making life easier and brighter--to my own life.

The premise is: use the point-in-time messages and notifications I receive to execute meaningful actions with them.

Here's an incredibly simplified diagram to show you what I mean:

![architecture diagram](https://images.ctfassets.net/zh68lrw89i3n/6NNqOu1wDlxoBzcqgxlDVm/9d388b8de048a402da1cda5917820869/Whiskey_diagram_export_Aug_28_2024.png)

So, as examples for use cases for this system.:
- When I get an email receipt, it can be stored automatically into my Documents for easy retrieval, and catalogued as a purchase for later reference
- When I get a text confirmation about an appointment, I can have a system automatically send the confirmation code.
- When something is successfully added to my Plex server, I can get a custom notification on my iPhone
- When I play a new song on my Plex server, I could automatically update a hypothetical 'now playing' widget on my [A-List website](https://a-list.mattwyskiel.com)

 > I am currently in the midst of re-architecting and re-documenting my setup, but in the meantime, please feel free to take a look around this GitHub organization anyways! Much is already out in the open with more to come.

## Stack
Since the goal is to have independent components working together, I leave room to vary the tools used based on the need met by each component. However, there are some things in common, mostly because they match my personal tool preferences.
- My cloud home is [Amazon Web Services](https://aws.amazon.com/), and the system (as re-architected) is based on events sent to [Amazon EventBridge](https://aws.amazon.com/eventbridge/)
- I prefer Serverless over Servers or Containers, mostly due to the cost savings at a scale as small as mine (currently 1 user :grin:)
- I use [SST](https://sst.dev) as my infrastructure-as-code toolbox.
- I typically use [Node.js](https://nodejs.org/en) (via [TypeScript](https://www.typescriptlang.org/)) as my backend base platform.
- I am firmly in the Apple ecosystem, so the [Apple Platforms](https://developer.apple.com) are my native-app home.


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
