---
title: "Modifying Expectations"
date: 2019-02-07T00:54:44-06:00
Description: "Modifying Expectations
Here, I’ll talk a little about how I have been accomplishing my project timeline. When we started the internship, the first requirement was to define a timeline for the project you were selected. This has to be discussed with your mentors, and if you do not have idea how it should be structured, it does not matter. They will help you and if something has to be changed (most likely to change) in the course, that is totally Okay."
Tags: ["Outreachy", "Kubernetes", "Contributor-Experience"]
Categories: []

---

Here, I’ll talk a little about how I have been accomplishing my project timeline. When we started the internship, the first requirement was to define a timeline for the project you were selected. This has to be discussed with your mentors, and if you do not have idea how it should be structured, it does not matter. They will help you and if something has to be changed (most likely to change) in the course, that is totally Okay.


## Project timeline ##

### Initially, this was my timeline: ###

**weeks 1 - 2**: These first two weeks will be dedicated to become familiar with the  documentation and learn the contribution process.

**weeks 3 - 4**: Read all off the material in /devel and get familiar with it.

**weeks 5 - 9**: learn about ownership of docs, how to figure out if docs are stale, and how to update stale docs.


This task includes:


* Finding holes in material that is implemented and not documented.
* Update stale documentation.
* Integrate docs created by others developers but that are not maintained.
* Consolidate things that are not documented from the Special Interest Groups that own files in the developer guide folder.


**weeks 10-12**: Put all pieces together and review with mentors. The last week we’ll have an updated developer guide.

I would say that the project timeline has been doing really good, even though the timing for every task has been somehow different as it was planned. For example; reading every single document, searching about unknown topics, asking on Slack, and in general becoming familiar with the docs in the /devel section of the kubernetes/community repository, took about six weeks. The initial plan was that it would take just four weeks.


After being familiar with the entire contribution process, then everything was so smooth that I was really happy about the speed change I got. First, I created an umbrella issue ([see the issue]) where all planned things were discussed with my mentors and other collaborators. Later, after a few revisions I started creating pull requests and others issues. All of this made that all the  planned things for weeks 5-9 were finished ahead of time.


At the time of writing this blog post, we have cleaned the Kubernetes developer guide folder and most of the documents have been reviewed and updated. Also, there were documents that were not relevant to the contribution process anymore, and that was because the information was  outdated. Those documents were deleted. So far, I have filed two issues ([second issue]) and have made twenty three  pull request that have been merged, and last but not least I have becomer member of the Kubernetes Organization with the priviledge of review code and pull requests. 

All of what I have achieved is in part thanks to the community. The Kubernetes community is amazing and you'll feel at home immediatly after you start contributing. Look what Christoph Beckler said about my contributions on the shoutouts slack channel.

{{< figure src="/images/slack.jpg" title="Shoutout on slack channel" width="60%">}}
<br/>

My internship is going to finish in four weeks. The last part is going to be about content creation. I already have created an skeleton with points I think we can add to the development.md document. Even though we already have high quality documents owned by every SIG ([see]), I believe there is a lack of certain information that can be very useful for both new and existing contributors. Seeing that, the plan for the next weeks is to have that information incorporated into the corresponding files.


I’ll keep you updated how this goes in future pots. Also, if you are applying to the Outreachy internship or are thinking of, let me know and I will be happy to assist you.


[see the issue]: https://github.com/kubernetes/community/issues/3064
[second issue]: https://github.com/kubernetes/community/issues/3097
[see]: https://github.com/eduartua/community/tree/master/contributors/devel