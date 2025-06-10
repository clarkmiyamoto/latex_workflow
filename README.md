# Latex Workflow
This is a parent repo for my latex workflow. It prevents you from having to upload the PDF to GitHub, and uses GitHub Actions to build & host the PDF.

# Usage
1. Fork this repo, and retitle to `<PROJECT_NAME>`.

For me, it is recommend to self-fork via:
```
git clone git@github.com:me/latex_workflow
cd latex_workflow
git remote set-url origin git@github.com:me/<PROJECT_NAME>
git push origin master
rm -rf latex_workflow
```

2. Place `.tex` (and related files) in the `tex/` folder.
3. Update entire `README.md` to
```
# <PROJECT_NAME>
Project description.

## 📄 Compiled PDF
[View compiled PDF](https://clarkmiyamoto.github.io/<PROJECT_NAME>/main.pdf)
```
So for example, the example PDF in this repo is uploaded to https://clarkmiyamoto.github.io/latex_workflow/main.pdf.

4. Finally! Add, commit, and push.

# Assumptions
- Main tex file is `tex/main.tex`.





