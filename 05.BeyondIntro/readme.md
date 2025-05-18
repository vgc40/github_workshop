# Well, what else can you do with a repo?
That was great! We made a repo, cloned it, made changes on our local pc and pushed them to the github cloud, and even compartmentalized some R code for easy downstream work. 
But guess what, there's even *more* we can do!

## Alternate timelines

One of the coolest things you can do is create alternate [branches](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches) within your repo, to do things like test out new methods without changing the original branch. 

## Integrating with apps

You can have github directly in R, Visual Studio Code, TeXstudio, and other programs. That's a bit outside of the scope of this workshop, but it's possible!

## Gitignore, very important for those of you workig with large data files

While Github is amazing, unfortunately it doesn't handle data files larger than 100mb. This isn't a problem most of the times, as you can use little tricks in R to save the output of large Bayesian models in compressed format, but it is a particular problem for spatial datasets. One way you can get around this being an issue is by using Git ignore. There is a guide [here](https://www.w3schools.com/git/git_ignore.asp), and essentially what you do is mark folders or file extensions so that they're automatically ignored when pushing/pulling on git. 

## How do you learn more?

I actually just learned about this, but the [Github Student Developer Pack](https://education.github.com/pack) is free for students! However, you do need to authorize your student status, so I would recommend not doinng this until you are on campus. 
