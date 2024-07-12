# ROB 311 

This repository contains documentations for ROB311 How to Build Robots and Make Them Move. 

Every git push will trigger one github action results in updates on the website.

## How to modify the files on github:
Simply using the edit feature on GitHub is sufficient. Once you save, the GitHub Action will automatically build and deploy everything. This is the best method for quick typo fixes. 

## How to modify the 550 docs site locally:
1. Install Jekyll: install all the prerequisites following the instruction there: [Jekyll doc](https://jekyllrb.com/docs/)
2. Since we already have the site, after install jekyll and bundler gems by running `gem install jekyll bundler`, we can `cd` to this folder `rob311-docs.github.io`, then run
    ```
    bundle exec jekyll serve
    ```
    - You might encounter error for the first time set up, you need to run `sudo bundle install` as the error message indicates, then run the command above.

We are now hosting the website locally, and it can be accessed at http://localhost:4000. Once you have completed your changes and run git push, GitHub Actions will automatically apply the updates to your website.
