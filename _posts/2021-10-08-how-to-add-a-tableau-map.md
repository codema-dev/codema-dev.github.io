---
layout: splash
date: 2021-10-08
title: How to add a Tableau Map to this Website
categories: blog
tags:
  - tutorial
  - Tableau
---

<style>
.centre {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
}
.alert {
  padding: 20px;
  background-color: #d3d3d3; /* Light Grey */
  color: white;
  margin-bottom: 15px;
}
</style>
 
- Create & publish your map to Tableau Public

- On your Tableau Public map click `Share`, copy the `HTML` in `Embed Code` and paste it to [htmlbeautify](https://htmlbeautify.com/) - you can now copy & paste this code to the website

- Fork the [website's Github](https://github.com/rdmolony/codema-dev.github.io) (see [here](https://guides.github.com/activities/forking/)) - this creates a copy of the website just for you. 

<div class="centre">
  <img width="259" alt="fork" src="https://github-images.s3.amazonaws.com/help/bootcamp/Bootcamp-Fork.png">
</div>

<div class="alert">
  <details>
    <summary>Already forked?</summary>
    Make sure your gh-pages branch is up to date
  </details>
</div>

- On your fork add a new branch (see [here](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches)) - this creates a sandbox in which you make changes to your hearts content, and delete if needs be!

<div class="centre">
  <img width="259" alt="add-branch" src="https://user-images.githubusercontent.com/50016440/134347523-80dc5710-ece8-42d1-b807-68954ee6ce11.png">
</div>

- Click `_posts` > `Add file` > `Create new file`

<div class="centre">
  <img width="222" alt="add-post" src="https://user-images.githubusercontent.com/50016440/134348307-59cae177-8207-4cd9-9123-3414a6ec957f.png">
</div>

- Create a new file called `YYYY-MM-DD-filename.md` (ex: `2021-09-22-marine-atlas.md`) and add your content.  

> The section between the `---` symbols defines the metadata about your page (copy & paste the metadata [from another post](https://github.com/codema-dev/codema-dev.github.io/tree/gh-pages/_posts), or for more information see [here](https://jekyllrb.com/docs/front-matter/) for options, [here](https://mmistakes.github.io/minimal-mistakes/year-archive/) for sample posts and [here](https://github.com/mmistakes/minimal-mistakes/tree/master/docs/_posts) for the sample posts Github)

<div class="centre">
  <img width="950" alt="add-content-zoomed" src="https://user-images.githubusercontent.com/50016440/134348872-a5d05e78-9dea-435a-9b51-0b0dea4c9b9e.png">
</div>

- Commit your new file to your branch

<div class="centre">
  <img width="950" alt="commit-file-zoomed" src="https://user-images.githubusercontent.com/50016440/134355523-1f8df6ab-148c-427c-9e42-84d5eff1338d.png">
</div>

- Preview your edits by clicking `Settings` > `Pages` > `Source` and selecting your branch

<div class="centre">
  <img width="796" alt="setup-github-pages" src="https://user-images.githubusercontent.com/50016440/134355351-ac486234-821e-4d19-bb76-b2beaa262575.png">
</div>

- When you're happy with your edits go to [website's Github](https://github.com/rdmolony/codema-dev.github.io) and accept the "Would you like to submit a Pull Request" prompt

> Or click `Pull Requests` > `New Pull Request` > `compare across forks` and select your fork for `head repository` and your branch for `compare` and finally `Create Pull Request`

<div class="centre">
  <img width="933" alt="create-pull-request-zoomed" src="https://user-images.githubusercontent.com/50016440/134357269-71aa5d74-5f3f-46de-b735-55dc561a826d.png">
</div>

- After a final review of the post, merge the changes in and delete your branch if you like!
