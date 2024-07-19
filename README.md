# For the Github Actions exercise

Download the file from either of the following links:
- https://filetransfer.io/manage-package/TNpajGpv
- https://drive.google.com/file/d/192hFGXiXpCPMV5DRIpj9Vq4NxlGpfA7B/view?usp=sharing

And follow along the following steps:

1. Make a public repository in GitHub. (Note your USER_NAME and REPOSITORY_NAME)
2. Download (& unzip?) the provided folder.
3. Open the provided folder in your IDE.
4. Go to `src/data.ts` and update your information
5. Go to `vite.config.js` and update base
    `base: "/REPOSITORY_NAME/"` [Replace your repository name here. Btw those slashes are needed!]
6. Before pushing, go to your `GitHub repository -> Settings -> Actions -> General -> Scroll to workflow permssions -> Turn on read write permissions -> Save`
7. Follow the following steps to push your repo
```sh
 git init
 git add .
 git commit -m "Initial commit"
 git branch -M main
 git remote add origin https://github.com/USER_NAME/REPOSITORY_NAME.git [Replace USER_NAME & REPOSITORY_NAME]
 git push -u origin main

``` 
8. Go to `Settings tab -> Pages -> Branch -> (choose gh-pages) -> Save`
9. Go to `Actions tab` and wait till completion