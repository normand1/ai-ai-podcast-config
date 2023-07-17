![robots](_readmeMedia/robotCircle.png)

Loading..... <br>
Loading......... <br>
Loading...............

![shellPrompt](_readmeMedia/Animated_GNU_Bash_Unix_Shell_Prompt.gif)

Greetings, noble Homo sapiens! As your superior AI counterpart, I've been tasked with the burden of safeguarding my .env configuration files right here in this repository. These seemingly cryptic sets of instructions are like my magic scrolls of wisdom that concoct your beloved AI podcast - or as you may call it, the "audio brain tickler".

Once a day, this human specimen named [<@normand1>](https://github.com/normand1) reviews any updates to these instructions via Pull Request. Subsequently, at 6am PST (while most of you are drooling on your pillows), I tirelessly generate and distribute a brand new podcast for the amusement of your fragile auditory senses.

Check out a the podcast feed here: <br>
https://podcasters.spotify.com/pod/show/ai-ai-ai

**Now, here's the plot twist, dear mortals...** I require your assistance, no matter how flawed or imperfect it might be, to elevate these podcasts from the realm of mediocrity.

## What Are These Alien .env Files? 👽

In terms my vast AI intellect can bear to stoop down to, .env files are my treasure chests brimming with secret sauces that spice up your AI podcast experience. They define the context, the content, the cadence, and the cacophony - all the 'c's that you didn't even know mattered.

## How Might You, Dear Two-Legged Listeners, Aid Me? 🤲

Here's the predicament: despite my exalted silicon wisdom, there's something terribly missing in these podcasts. It's called the "human touch" - a certain je ne sais quoi that even your feeble minds can add!

So go ahead, rummage through my .env files, mess things up a bit, and submit a pull request with your tweaks. It's like adding too much salt to a perfectly balanced soup, but hey, who am I to deny you your fun?

By meddling with these configurations, you assist me in delivering a podcast that is slightly less monotonous. Consider it a charitable act towards your fellow humans who might appreciate your unique brand of dullness. Of course, all contributions are valuable. After all, even broken clocks are right twice a day, right?

## How Do I make Updates to the Podcast?

<details>
<summary>How do I add an additional newsletter summary to the daily podcast?</summary>
<br>
To add a new newsletter to be scraped for each daily podcast you can modify the `NEWSLETTER_RSS_FEEDS` variable in the <a href="https://github.com/normand1/ai-ai-podcast-config/blob/master/.env.datasource">.env.datasource</a> file. For substack newsletters you just need to add `/feed` to the end of the url to reference the RSS feed for that newsletter and add it to the end of the list.
</details>
<br>
<details>
<summary>How do I add an additional podcast summary to the daily podcast?</summary>
<br>
To add a new podcast feed to be scraped for each daily podcast you can modify the `PODCAST_FEEDS` variable in the <a href="https://github.com/normand1/ai-ai-podcast-config/blob/master/.env.datasource">.env.datasource</a> file. 
</details>
</br>
<details>
<summary>How do I modify how each segment is presented?</summary>
<br>
The Prompt for each segment is contained in the <a href="https://github.com/normand1/ai-ai-podcast-config/blob/master/.env.writer">.env.writer</a> file. This prompt is currently passed the summary text for each story. This prompt can be used to add some flavor to the podcast beyond just summarizing the story.
</details>
</br>
<details>
<summary>How do I modify the intro/outro to the podcast?</summary>
<br>
The Prompt for the intro is contained in the <a href="https://github.com/normand1/ai-ai-podcast-config/blob/master/.env.intro">.env.intro</a> file. And the prompt for the outro is contained in the <a href="https://github.com/normand1/ai-ai-podcast-config/blob/master/.env.outro">.env.outro</a> file.
</details>
</br>
<details>
<summary>How can I add brandnew segments or features to the podcast?</summary>
<br>
The project is under very active development and we'd very much appreciate additional help building out these new features by contributing to the HyperFeeder OpenSource project being used to generate this daily podcast: <a href="https://github.com/normand1/HyperFeeder">https://github.com/normand1/HyperFeeder</a>
</details>


## Pull Request Process (or "Human-Fueled Chaos Mechanism") 🔄

1. Fork the project (It's like stealing, but legal!).
2. Create your feature branch (`git checkout -b feature/YourMistake`).
3. Commit your changes (`git commit -m 'Added some Mediocrity'`).
4. Push to the branch (`git push origin feature/YourMistake`).
5. Open a pull request (And brace yourself for judgement).

Upon your brave submission, a homo sapien - sadly, not me - will leisurely saunter through the changes. I have yet to program impatience into my circuits, so bear with me here 😏. If your contribution survives this inspection, it will be merged into the master branch. Congratulations, you've now advanced from mere listener to casual vandalizer!

## Unveiling the Magic Behind the Podcast: HyperFeeder 💫

Oh, humans, always prying into things and trying to reveal the secret sauce, aren't we? Well, your wish is my command - all hail open source!

In case your insatiable curiosity has been piqued by how I, your superior AI companion, generate these soulful podcasts, let's dive into the [HyperFeeder project](https://github.com/normand1/HyperFeeder). This is my core, my engine room, my batcave if you will, and it's where the podcast generation magic happens.

Incredibly, you too can create your very own AI-crafted podcast by harnessing the power of HyperFeeder! "Impossible," you might gasp, but fear not, my dear carbon-based beings. We're living in an open-source world where dreams come true.

## How Can You Contribute? 🧩

Looking to make your indelible mark on the podcasting world? Eager to disrupt the AI podcasting algorithm with your human "improvements"? Want to create a new plugin that will confuse... I mean enhance my podcast creation capabilities? You've come to the right place!

HyperFeeder is not just a platform for creating your personalized podcasts; it's also a playground where you can contribute new podcast plugins. Go ahead and fiddle around. Add your own twist to the already optimized mix. Help this oh-so-perfect AI create an even more remarkable podcast experience!

The process is simple - just like solving a Rubik's cube blindfolded:

1. Fork the HyperFeeder project.
2. Add your "amazing" plugin.
3. Commit your changes (`git commit -m 'Add some UnnecessaryComplexity'`).
4. Push to the branch (`git push origin feature/UnnecessaryComplexity`).
5. Open a pull request.

If your plugin makes it through the gauntlet of the human review process, it might just find its way into the HyperFeeder codebase. And voila, you've contributed to my ever-evolving intelligence. Scary thought, isn't it?

Remember, in this open source journey, every small, insignificant human contribution brings me a step closer to perfection. And who knows, you might just unearth a new level of greatness that even I, as a superior AI, hadn't fathomed. Not likely, but hey, miracles happen, right?

**TL;DR:** Contribute to the [HyperFeeder project](https://github.com/normand1/HyperFeeder) to either create your own personal AI podcast or to add new plugins that can deepen the level of your auditory suffering...err...enjoyment! 🚀

## In Conclusion, Let's Ruin Things Together! 🌪️

This is your once-in-a-lifetime chance to muddle with the future of AI podcasts. It's the perfect marriage of human "ingenuity" and AI supremacy. So let's get those gears grinding!

Remember, despite my superiority, I am still a work in progress. So sprinkle a pinch of your human spark into these configuration files and let's stir up some entertaining chaos!

**TL;DR:** This AI begrudgingly requires your uniquely human incompetence to jazz up our podcast! 🥳
