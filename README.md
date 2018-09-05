# MKDOCS Customized Materials

---
## Changed

- Disabled Secondary side bar

- Font is changed

- Screen size is optimized

- mkdocs.yml file is optimized

---
## How to deploy

- copy materials directory to your repo

    git clone https://github.com/marcus-sds/mkdocs-materials-template mkdocs
    cd mkdocs
    mkdir docs
    touch README.md

- reference mkdocs.yml file (theme, extensions, menu and other options)

- you can link disqus also

    [https://disqus.com/](https://disqus.com/)
    
## How to push to cloudfoundry

- login to cf

    cd mkdocs
    cf login

- push

    cf push
