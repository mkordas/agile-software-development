# Code Reviews

* Should be mandatory
* Test whether code can be understood just by reading
* Takes anytime between 3 minutes and 3 hours

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

### How many

* review own code
* first reviewer 50% issues
* second 25% issues
* next ones may be a waste
* gathering votes e.g. with `:+1:`

### Contents

* small changes
* features, bugfixes, refactorings should not be mixed
* document PR
* add meaningful commit messages

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
* OK to disagree or argue
* there are many ways to solve problems
 * do not argue to solve everything your way
 * reject if doesn't meet quality standards

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
