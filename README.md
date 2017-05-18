# GitHupdates
The wild, wonderful world of open-source software is difficult to constantly stay in the know.  If there were more hours in the day, we could all work, maintain our relationships, contribute to open-source software, enjoy leisure and sleep a healthy amount each night.  That's all fine and dandy but it's not going to happen, my dude.

Ah, forgot to mention that you need to keep up with the copious __GitHub__ projects' releases and current state.  I guess you could include other stuff like eating and exercising but let's not get ahead of ourselves.

----

I was visiting my girlfriend in Washington D.C., who works for a U.S. Senator, when I was complaining to a coworker about taking even a few days off from hawking project updates would set me back even more than those few days that I am in D.C.

I then asked this coworker how their staff gets caught up to speed when vacationing.  The coworker mentioned a briefing document with the highlights of events/happenings that occured while the person was away from D.C.

The obvious next question that popped into my head:  why couldn't this be done for __GitHub__ Projects?

----

## Here we are

In the same vein of popular "flash updates" such as Amazon Alexa's verbal flash briefings or a tool like [TweetDeck](https://tweetdeck.twitter.com/), *GitHupdates* will allow a user to get caught up to speed with any of the __GitHub__ projects that they desire, without the fluff.

----

## Brainstorming
Utiizing GitHub's API, this tool will filter out the junk and you can kiss the cluttered GitHub homepage goodbye.

- View a project's changes
  - Over the project's lifetime
  - Over a specified date-range (1 week ago from today)
- Create a hierarchy of comments/interactions
  - High-volume of comments emphasize the topic is desired by many and users are actively engaging
    - Sudden bursts of comments within a isolated datetime-range indicate a potential issue or better solution
    - A resolved issue/thread suddently receiving a burst of comments indicates a potential issue or better solution
  - Emojii responses (thumbs up, smiley faces, etc.) to comments can indicate positive or negative
    - A user receiving thumbs down may have asked an inappropriate question or provided an incorrect solution
    - A user receiving thumbs up and praise may have provided a solution to the original issue
    - A thread that was resolved sees a resurgancy of new posts with positive/negative emojii responses
    - These determine user engagement for that particular issue and can aid in determining its importance/popularity
  - Key words in comments and their sibling comments can provide more information about the post
    - "Thanks, that worked", "FINALLY!" may indicate that the user they are responding to solved their problem
    - "Does not work still" may indicate that the provided solution is not all-encompassing and should be revisited
- Utilize the hierarcy of comments/interactions to see how they pertain to the roadmap or defined project goals.
  - While the comments/interactions may be relevant long-term, it may be solely for an upcoming release
  - Provide highlights of the highly-engaged content for users to sift through the issue/thread
  - Take "important/popular" comments and their surrounding context to offer a summary of the issue and/or resolution
- Weight the contributions of Collaborators / Maintainers / Managers of the project more heavily
  - A group of collaborators discussing an issue indicates that it is of important note
  - A collaborator responding to an issue may point the user to a necessary thread or aide them solving the problem
    - Traveling to a different thread for a solution that already exists would be filtered
    - Solving the problem for the user (assuming it is new to the collaborator) would be prominent & not filtered
  - Determine who receives more positive feedback across all threads and weight them more due to the assumption that they are active contributors to the project on a consistent basis.
- Pull Requests and how they relate to the roadmap, what is holding them back and the level of importancy
  - Pull Request's "age" waiting to be merged
    - It does not follow the roadmap
    - It has a failing test or awaiting more details or there is a roadblock
    - Check the comment activity to determine its importance and who is commenting on it.
    - Collaborator comments may affect the necessity of a particular PR
- Releasing the project
  - Check for any updates to a __GitHub__ projet's "Roadmap" section,.
  - View the posts pertaining to any roadmap options & specifically look for roadlblocks.
- On new releases, determine a way to extract the most important bullet points from the release document/page and

## Down the road
- The ability to quickly switch between GitHub projects to review their updates within the tool.
- Integrate with internal/other 3rd-party version control applications
- Group certain GitHub projects that may depend on a certain pull request to encourage tackling that issue first
- Allow people to know specific holdups to A) complain or B) attempt to help expedite the process :)
