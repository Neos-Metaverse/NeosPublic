# NeosPublic
A public issue and roadmap only repository for the NeosVR project.

## Recent Steam Changes
If you're curious on the recent Steam changes we have a [wiki page dedicated to that](https://wiki.neos.com/Neos_Credits/Steam_Changes).

You can also download Neos through a [direct link](https://assets.neos.com/install/NeosPublicSetup.exe). This is not Neosine, its a temporary launcher.

## DO's and DON'Ts
- DON'T use vague statements and measurements (e.g. "It took too long", "I have encountered problems/examples"). Those are subjective and could mean anything, which can make it difficult for us to assess the problem.
- DON'T hijack existing issue for a similar, but different problem - we generall focus on the issue reported in the original post and won't address other issues mentioned in comment unless they're the same problem. Please make a separate issue instead.
- DO be specific - e.g. "It took roughtly 10 minutes" or explain what exact problems and examples you found. Simply stating that there are problems or use-cases isn't enough.
- DO provide information on regressions when was the last time (at least approximatelly) the feature worked and how do you know that it worked before, so we can evaluate regressions properly
- DO check if the issue happens on the latest build if you can. Sometimes we have already released fixes for certain issues or made some related changes. If you are reporting issues that last happened on very old builds, they will not likely get prioritized unless they can be replicated on the latest build as well. Similarly logs from very old builds will not be very useful for diagnosis, as the code might've changed significantly since.
- DO paste the actual quote/conversation from external sources (e.g. Discord) into GitHub, instead of just linking them. Following those links can be tedious on our end as it requires logging in, switching applications, resulting in those issues being shelved for later and getting lower priority as a result.
- DON'T use entire conversations from external channels as the issue or response to questions in the issue. Please post a summary instead or answer to the specific question. If we need to read a longer conversation to get answer to the question, we'll less likely prioritize the issue over ones that provide clear and succint summaries.
- DON'T use vague issue titles, for example "xyz should be nicer to use" or "xyz should have more functionality". When we can't tell what the issue is about specifically from the title, it's much less likely we'll pick it up when looking for issues to prioritize, as it requires us to open the issue to learn what it's about, instead of just going through the list of issues.
- DON'T paste partial log files or screenshots of log files. We need the whole log file from your computer, drag it into the new issue form.

## What are Issues?
Issues are used to discuss items such as Bug Reports, Feature Requests and Documentation requests with the Neos Team. You can find the issue list [here](https://github.com/Neos-Metaverse/NeosPublic/issues)

If you'd like to make a new issue you can [click here](https://github.com/Neos-Metaverse/NeosPublic/issues/new/choose) to start the process. You'll need a GitHub account to make issues and one can be created by [clicking here](https://github.com/join)

## Security issues or exploits
Please do not submit security exploits to the public GitHub. You can report them privately at https://moderation.neos.com .

For more information please read our [security and exploit reporting policy](./.github/SECURITY.md).

## Inter-personal issues and requests
If your issue directly relates to another user or group rather than a general bug or feature requests for the software, please make a ticket at https://moderation.neos.com instead.

## Before you create issue or comment
- Be as descriptive as possible. Explain what happened prior to problem, what does the problem look like and what you expected instead. The better the description, the less back and forth will be needed and the greater likelihood of getting the issue solved
- If you experience a problem, make sure it’s reported. If you wait for someone else to report it instead or the developers to notice themselves, it might not get fixed for a long time (or at all)
- See if you can find a way to reliably replicate the bug. If the developers can reproduce the bug on their end, it significantly helps with its resolution
- If you experienced a bug, including the log files can significantly help in resolving the issue. See here how to find the logs: https://wiki.neos.com/index.php?title=Frequently_Asked_Questions#Where_can_I_find_log_files.3F
- If you have crashed, frozen or encountered hardware issue, include the additional Unity log as well.
- If you have crashed or frozen, check for crash dumps and include those as well
- Even if your exact suggestion isn’t implemented, it’s still very useful, because it helps us see what issues you’re dealing with and incorporate those into future decisions, or address the problem in an alternate way
- Please keep issues on topic and conversation calm and factual. Bringing emotion makes issues harder to deal with and will only hurt their resolution and impact our overall development speed. Remember we're human as well.

## Discussing issues with others in Discord
If you're unsure about an issue and want to ask others or solidify your report before you post, you can use the #bugs-and-feedback channel in our official Discord (https://discord.gg/neosvr). Please be aware that things can get lost in the flow of conversation or might not get immediate response. If you want to make sure the issue is logged and doesn’t get missed, always log it on GitHub after the discussion.

## I have issue with model or other asset I’m importing
Due to a wide variety of models, rigs and types of files, not all of them will import correctly. You might encounter things like:
- Vertices being randomly messed up, stretching where they shouldn’t (either with static model or when using blendshapes)
- Model failing to import at all or crashing Neos
- Fingers being mangled after avatar is equppiped

If you can share the model file itself, send it over to developers for testing. This significantly increases the chance of the issue being fixed, as we can analyze what is going wrong with the file.

## When is a feature going to be implemented or a bug fixed?
At any time, there are many different features and issues that we’d like to implement or fix, but there’s only a few that can be worked on at the time. There are several factors that determine the priority:
- **Severity**: If it’s something with serious global impact on usability or security of users, it will be very high on the list.
- **Demand**: The more people request a given feature or issue to be fixed, the higher its priority. This changes over time, so don’t hesitate adding your voice even if it was already requested. Becoming a supporter or donating will give your requests higher priority as it helps grow and support our team
- **Complexity**: Some things are significantly quicker to implement/fix than others. If something is a trivial fix it might get addressed very quickly even though it doesn’t have as high demand or severity
- **Prerequisites**: Certain features or issues cannot be (efficiently) addressed without other, much bigger features or architectural changes done first. Our goal is long term sustainability and stability of the codebase, so certain things can take a lot longer to get addressed despite the demand. We will try to communicate whenever this is the case.

Note that the priorities are constantly shifting and evolving based on the feedback and demand from you, the community. If something is determined to be low priority at the moment, it doesn’t need to stay that way, just make sure your voice is heard through the right channels and we’ll listen!

If the request is not feasible on our end, we'll try to offer alternatives or explain why it can't/won't be implemented. We knows it sucks getting a request denied, but we'd rather be upfront about it rather than give an empty promise on something we know we can't deliver.

### Feature/Issue Prioritization

Neos & The Neos Team prioritizes work using a number of signals and factors. These factors all mix together into a final decision through discussion with the Neos Team. These factors are(but not limited to):
- Neos' Roadmap & Plans
- Neos' Limitations - We're in some cases waiting on or dependant on other features or 3rd parties.
- Neos' Business Needs
- GitHub Thumbs Ups
- Patron Issue Voting
- The needs of the Neos Team
- The needs of the Community
- What the Neos Team CAN work on
- What the Neos Team WANT to work on

These factors are not explicitly ordered as ALL of them factor into the decision making process.  

We understand that users may be frustrated in the order in which we work on things or that we're not working on what they want us to work on but the best thing you can do is to continue to work with us in voting on issues, providing us feedback and making GitHub Issues.

Sometimes you might also see certain features being done out of order completely. Developing can be quite draining task sometimes and we like to work on certain things just for fun or for the satisfaction of it to refocus our brains. Plus it makes sure that certain low demand, but nice things get attention from time to time too!

### Voting on issues
You can vote on any issue by clicking the Emoji button at the top right of the original post and adding a +1 (thumbs_up). This allows the issue queue to be sorted by number of reactions.
- [Issues sorted by votes](https://github.com/Neos-Metaverse/NeosPublic/issues?q=is%3Aissue+is%3Aopen+sort%3Areactions-%2B1-desc)

### Patreon supporter priority voting
If you're a Patreon supporter you can also vote on the issues by sending `/priorityIssue <issue number>` command to the "Neos" bot account in Neos (make sure your Neos account is actually linked to Patreon). Currently you can have 1 issue set as your priority, you can change your vote at any time. The score is proportional to the level of support.
- [Patreon Priority Issues](https://api.neos.com/api/stats/priorityIssues)

## Roadmap

This repository also contains Neos Roadmap, you can find this [here](https://github.com/Neos-Metaverse/NeosPublic/projects/1)

