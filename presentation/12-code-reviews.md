# Code Reviews

* Should be mandatory
* Test whether code can be understood just by reading
* May take anytime between 3 minutes and 3 hours
 * it's normal that some reviews take huge amount of time

![](https://cdn.meme.am/instances/500x/63499131.jpg)

### Purpose

* finding bugs (?)
* knowledge sharing
* increasing bus factor
 * if not anyone commits everywhere then at least reviews should be shared
* onboarding new team member
* bringing new ideas, libraries and tools
* revealing problems and risks
* great moment to ask questions

### Not Purposes

* to evaluate performance

### Automation

* Do not substitute quality practices
* Not a place for code style wars
* Any complaint to style/convention/common bug should have follow-up to be automated

### Never Assume Code Is Good

![](http://i.stack.imgur.com/dLTF8.png)

### Code Review Culture

* feedback skills
 * code is personal, there is always person behind it
 
![](https://davidwalsh.name/demo/code-review-2.jpg)

### How many

* review own code
* first reviewer 50% issues
* second 25% issues
* next ones may be a waste
* gathering votes e.g. with `:+1:`

### Contents

* small changes
![](https://pbs.twimg.com/media/CIXISVyWIAAfe8U.jpg)
* features, bugfixes, refactorings should not be mixed
* document PR
* add meaningful commit messages

![](http://s2.quickmeme.com/img/0e/0ee676a657e4f108f1ff2c9a48d35b78823c2d8b9268922d6f5ace8fed9679fe.jpg)

### Aspects

* simplicity
* reusability
* SOLID, DDD
* new dependencies
* security

### How?

* have discussion, do not dictate
* ask questions to give credit to author
 * did you consider...
 * what hapens if...
 * did you think of that
* it's OK to disagree or argue
* never compromise
* there are many ways to solve problems
 * do not argue to solve everything your way
 * reject if doesn't meet quality standards
* try to provide full feedback in one go in timely manner
 * author can start fixing code without being distracted with new comments
 * `on it` comment when starting
 * `see my comments` when done
* make clear what type of comment it is
 * important issue/question that needs to be answered
 * minor style comment
 * suggestion for next time
 * subjective opinion while being fine with the current code

![](http://www.thailandqa.com/forum/attachment.php?attachmentid=19238&d=1378108562)

### Receiving feedback

* stop for a 5 minutes
* give a thought
* ask questions, discuss
* explain reasoning

### Possible review outcomes

* you are right, I take my comments back
* let's ask mediator
* discuss topic on design session
* not accepted

### Convincing

* never by amount of experience or position
* emotions, offence, angriness is not professional
* even if code is trash point issues one by one
* articles, books, blog posts, Javadoc, StackOverflow
* reviewer should prove he/she is right, not the other way round
* if no valid resources behind your comments, probably you're not right


### Sample Reviews

* https://github.com/kubernetes/kubernetes/pull/33262
* https://github.com/apache/spark/pull/15090
* https://github.com/checkstyle/checkstyle/pull/2177

![](http://img.memecdn.com/How-To-Make-A-Good-Code-Review_o_49060.jpg)
