Source for rinaldo-rex.github.io
---

Points to remember:
 - Uses mdbook as the static site generator. 
    - Also uses the following mdbook preprocessor plugins:
        - mdbook-footnote
        - mdbook-reading-time
    - Enabled mathjax support for subscript/superscript.
 - Checkout the `.github/workflows/mdbook.yml` file for the configurations of automated build and deploy. 
    - Uses Github Actions
    - Pushes/deploys to master branch (Since user pages on github pages are accepted only on master)
