# DataVizandAI

## Repo for articles

**Instructions**

All repos are in  `projects/blog/DataVizandAI`

Articles are in the '**source**' repo along with all source code. This repo is private so we can have API keys, notes, experiments, etc.

All new articles should be in their own folder in '**posts**' (old articles are not necessarily like this and some are simply references to Medium articles).

Build the blog with: 

```
 bundle exec jekyll serve
```

or from this folder

```
./runjekyll.bat
```


It will pick up all files in the form `yyy-mm-dd-articlename.md` even in subfolders.

Check locally that the site is ok.

Copy the site folder to the main **DataVizandAI** repo overwriting all files (there are additional files in the repo that are not overwritten, e.g. README.md)

Public code should be copied across to the '**pubic_code**' repo in a folder of the same name. All images that go with the article should be here, too. Only copy across relevant file not .venv and so on.

### GitHub

Synch all repos with GitHub desktop.

View repo on Github from a browser signed in as rayandcelina


### Medium

Cut and paste from a markdown preview into the Medium editor. Review carefully - the code blocks, in particular, may not render correctly. 

### Substack

Same as Medium

### Towards Data Science

To get a PDF use Pandoc. 
