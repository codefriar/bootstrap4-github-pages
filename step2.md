# Forking the repositories
Alright, go get a lovely beverage and lets get started. These next few steps are a bit of a breeze, so you'll need a lovely beverage. I trust you’re familiar with GitHub? We created and maintain a couple of example repositories on GitHub. They hold just-enough of an application to demonstrate a 3 layer architecture. In the three-layer architecture you have a Front-end, a Back-end and a Database. Our example builds on the MERN stack, and if you’re new to that, it’s ok. You don’t need to know anything about Mongo, Express, React or Node(MERN) to complete this guide.

You do have to make your own clone of our two repositories. But wait, you say, you said there’s three layers, but only two repositories? Good catch, my eagle-eyed friends. The first repository, found here: [https://github.com/harness-apps/MERN-Stack-Example](harness-app/MERN-Stack-Example) contains the application. All of the frontend and backend code is there. The second repo over at:  [https://github.com/harness-apps/MERN-Stack-Example-GitOps](harness-apps/MERN-Stack-Example-GitOps) contains the GitOps / GitOps configuration. Why separate them? Because GitOps that's why. Now I don’t want to tweet all preachy but GitOps is a great thing. Keeping all-things deployment related in Git ensures your ops team is in control.

So, here’s what you need you to do. Login to GitHub, and visit these two repositories and fork them. You’re going to need to own these repos in order for them to show up in the Harness UI. That means you must fork, not clone. Now this guide is all about CI, so I’m going to [https://docs.github.com/en/get-started/quickstart/fork-a-repo](hand off to Air Traffic Control in GitHub for details on how to fork.) The two repositories you need to fork are:

- [https://GitHub.com/harness-apps/MERN-Stack-Example](harness-apps/MERN-Stack-Example)
- [https://GitHub.com/harness-apps/MERN-Stack-Example-GitOps](harness-apps/MERN-Stack-Exampel-GitOps)

In later steps, you’re gonna need to know your forked repo URLs, so note them down. 

<a class="btn btn-primary" href="/step1.md">Wait, back up...</a>
<a class="btn btn-primary" href="/step3.md">Got it! Let's keep going</a>