# STUFF FOR MY BLOG

https://jhagas.github.io/blog

© Jhagas Hana Winaya\
Licensed under CC-BY-SA 3.0

## Software I Use to Build HTML From Markdown

This is the software i use to build this site, and the installation command (in Arch Linux)

1. Script Written in GNU Bash + GNU Core Utils
    ```
    git clone "https://github.com/jhagas/blog"
    ```
2. [Pandoc](https://pandoc.org/) (Converter md-HTML)
    ```bash
    sudo pacman -S pandoc
    ```
3. [Pandoc Static Katex](https://github.com/Zaharid/pandoc_static_katex) (Math rendering without js)
    ```bash
    # I Assume python3 is already installed
    python3 -m pip install pandoc_static_katex
    ```
4. [csso-cli](https://github.com/css/csso-cli) (CSS Minifier)
    ```bash
    # I Assume node.js and npm is already installed
    sudo npm install -g csso-cli
    ```
5. [KaTeX](katex.org) (Fast math interpreter in web technology. Integrated in script)

## How I Make an Article In My Blog?

1. Make new folder with format `word-word-word`.
1. Make new file `index.md` inside folder we created before.
1. Write an article using Markdown Syntax (Will be interpreted as Pandoc's Markdown).
1. Place the Main article picture in `images/judul.png`.
1. Place the other image files in `images/`.
1. Copy `articlebuild` into folder we created in step 1
1. Run `./articlebuild` to generate HTML file out of your Markdown Document. It also auto generate list for home folder.
1. Use Math formula? Don't worry, if the script ask you to use math, type `y` and `ENTER`
1. `cd ..` to main directory and execute git command to sync the change to Github Online Repository.
    ```
    git add *
    git commit -m "commit message"
    git push
    ```

## Let's Make Our Own Blog (IT'S FREE)

I encourage you to make your own simple blog in GitHub. Don't use Google's Proprietary Blogspot Site!! Also Markdown is a dead simple markup language. Everyone can learn it in **LITERALLY 5 MINUTES!!**

Just fork this repo and edit the Script Files, CSS, HTML whatever you want. Just make the code accessible to public as I do (CC-BY-SA 3.0).

