---
layout: posts
date: 2021-09-22
title: How to link this website to an existing map
categories: blog
tags:
  - tutorial
---

- Fork the [website's Github](https://github.com/rdmolony/codema-dev.github.io) (see [here](https://guides.github.com/activities/forking/)) - this creates a copy of the website just for you. 

<img width="259" alt="fork" src="https://github-images.s3.amazonaws.com/help/bootcamp/Bootcamp-Fork.png">

- On your fork add a new branch (see [here](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches)) - this creates a sandbox in which you make changes to your hearts content, and delete if needs be!

<img width="259" alt="add-branch" src="https://user-images.githubusercontent.com/50016440/134347523-80dc5710-ece8-42d1-b807-68954ee6ce11.png">

- Click `_posts` > `Add file` > `Create new file`

<img width="222" alt="add-post" src="https://user-images.githubusercontent.com/50016440/134348307-59cae177-8207-4cd9-9123-3414a6ec957f.png">

- Create a new file called `YYYY-MM-DD-filename.md` (ex: `2021-09-22-marine-atlas.md`) and add your content.  

> The section between the `---` symbols defines the metadata about your page (see [here](https://jekyllrb.com/docs/front-matter/) for options, [here](https://mmistakes.github.io/minimal-mistakes/year-archive/) for sample posts and [here](https://github.com/mmistakes/minimal-mistakes/tree/master/docs/_posts) for the sample posts Github)

<img width="950" alt="add-content-zoomed" src="https://user-images.githubusercontent.com/50016440/134348872-a5d05e78-9dea-435a-9b51-0b0dea4c9b9e.png">

- Commit your new file to your branch

<img width="950" alt="commit-file-zoomed" src="https://user-images.githubusercontent.com/50016440/134355523-1f8df6ab-148c-427c-9e42-84d5eff1338d.png">

- Preview your edits by clicking `Settings` > `Pages` > `Source` and selecting your branch

<img width="796" alt="setup-github-pages" src="https://user-images.githubusercontent.com/50016440/134355351-ac486234-821e-4d19-bb76-b2beaa262575.png">

- When you're happy with your edits go to [website's Github](https://github.com/rdmolony/codema-dev.github.io) and accept the "Would you like to submit a Pull Request" prompt

> Or click `Pull Requests` > `New Pull Request` > `compare across forks` and select your fork for `head repository` and your branch for `compare` and finally `Create Pull Request`

<img width="933" alt="create-pull-request-zoomed" src="https://user-images.githubusercontent.com/50016440/134357269-71aa5d74-5f3f-46de-b735-55dc561a826d.png">

- After a final review of the post, merge the changes in and delete your branch if you like!
