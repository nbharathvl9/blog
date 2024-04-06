---
title: "Website Approach"
date: 2024-04-03T23:29:21+05:30
draft: false
github_link: "https://github.com/gurusabarish/hugo-profile"
author: "Bharath"
tags:
  - Hugo
  - Github
  - Terminal Commands 
image: /images/projects/hugo.png

toc:
---

# Hugo

To install Hugo on a local server, execute the command sudo apt hugo. After installation, confirm whether Hugo is installed by typing hugo server. Proceed by selecting a theme from the available Hugo themes. It is essential to thoroughly read and understand all instructions provided in the documentation. Following this,I created a Hugo site on the local server.

### Used Commands:
   -     hugo new site (type name of the site you want to creat)

   -     CD to root directory (into the site named file) then "CD" to themes
 
   -     cloned the git repository of the hugo theme (hugo profile) using [git clone url.git]


### Step-2


After successfully obtaining the theme on my **local server**, the next step is to modify its content to reflect my preferences. This involves replacing the **config.yaml** file in the **root directory** with the **config.yaml** file from the **examplesite** directory. By doing so, I gain access to customize various aspects such as the site's **name**, **social media links**, and other pertinent **data**.

However, the challenge arises when attempting to retrieve the **blog posts** and **images**, as they are not readily available on the server. To address this issue, it becomes necessary to replace the **content** and **static** folders in the **root directory** with their counterparts from the **examplesite**. Subsequently, in the **themes** folder, essential files and folders must be copied to the **static** directory.

Upon completing these steps, access to the **blogs** and **image gallery** becomes feasible, thereby allowing for further modifications and enhancements to the website's content.


### GitHUB pages

Once all necessary modifications and setup steps have been completed within the **portfolio** repository, the files are ready for upload to GitHub. Begin by adding all the files to the staging area using the command `git add .`, followed by committing the changes with a descriptive message using `git commit -m "Add the message"`. It's advisable to check the status of the repository with `git status` to ensure all changes are included. Finally, push the changes to the **main** branch of the remote repository on GitHub with `git push origin main`. 

On the GitHub website, navigate to the **portfolio** repository, go to the **Settings** tab, and open the **Pages** section. Change the option to **main** instead of **none** and save the changes. After refreshing the page and waiting for approximately 5 minutes, a link to the website will be generated. Repeat this process as needed for any further updates or modifications to the website.



### Used Code Blocks
-      cd

-      hugo new site #sitename

-      hugo server

