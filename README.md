# info-cern-ch2
# Unix/Linux commands from (Fluent) Terminal:

    mkdir ~/msimbo-projects/CodeChallenge1/info-cern-ch
    cd ~/msimbo-projects/CodeChallenge1/info-cern-ch
    rm -rf .git *html
    git init
    git branch -m master main
    touch overview.html
    touch what-is.html
    touch index.html
    code *.html
    echo "# info-cern-ch2" >> README.md
    git add .
    git commit -m "First commit"
    git branch -m master main
    git remote add origin https://github.com/a4ayad/info-cern-ch2.git
    git push -u origin main
  
