## Paper
\[WWW2021-FairGo\] Learning Fair Representations for Recommendation: A Graph-based Perspective \[[pdf](https://arxiv.org/abs/2102.09140)\] \[[code](https://github.com/newlei/FairGo)\] 

\[AAAI2020-LR-GCCF\] Revisiting Graph based Collaborative Filtering: A Linear Residual Graph Convolutional Network Approach \[[pdf](https://arxiv.org/abs/2001.10167)\] \[[code](https://github.com/newlei/FairGo)\]

\[TKDE2019-HASC\] A Hierarchical Attention Model for Social Contextual Image Recommendation \[[pdf](https://ieeexplore.ieee.org/document/8700213) [arxiv](https://arxiv.org/abs/1806.00723)\] \[[code](https://github.com/newlei/HASC)\]

## Dataset
### Flickr-collect and organize by myself
In TKDE2019-HASC, we collected Flickr data with rich information.

- Favor <user,item> matrix, e.g.:<1,2> denotes that user(id:1) favors item(id:2)

- Upload History <user, upload history item> matrix, e.g.:<1,[7,11,23]> show that user(id:1) uploads some items(id:7,11 and 23)

- Social Neighborhood <user, follow user> matrix, e.g.:<1,[5,6]> show that user(id:1) follows some users(id:5,6)

- Owner Admiration <item, owner user> matrix, e.g:<7,1> show that items(id:7) is uploaded by user(id:1)

- Item Visual Information <item, image visual feature> matrix, e.g:<2,[*]*4096> is the image feature of item(id:2)

F_L dataset, ensure each user and each image have at least 10 rating records. \[[download_link](https://mailhfuteducn-my.sharepoint.com/personal/chenlei_2016_mail_hfut_edu_cn/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fchenlei%5F2016%5Fmail%5Fhfut%5Fedu%5Fcn%2FDocuments%2Fpaper%2FshareFile%2FHASC&originalPath=aHR0cHM6Ly9tYWlsaGZ1dGVkdWNuLW15LnNoYXJlcG9pbnQuY29tLzpmOi9nL3BlcnNvbmFsL2NoZW5sZWlfMjAxNl9tYWlsX2hmdXRfZWR1X2NuL0Vscmd0Yy02aS1OSXZlRVBteDlZcWVzQkNTVUM4UWdSaVZuNUlPLVFiSWFheEE_cnRpbWU9UTJxbzBuVGMyRWc)\]

F_S dataset, a smaller but denser dataset. \[[download_link](https://mailhfuteducn-my.sharepoint.com/personal/chenlei_2016_mail_hfut_edu_cn/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fchenlei%5F2016%5Fmail%5Fhfut%5Fedu%5Fcn%2FDocuments%2Fpaper%2FshareFile%2FHASC&originalPath=aHR0cHM6Ly9tYWlsaGZ1dGVkdWNuLW15LnNoYXJlcG9pbnQuY29tLzpmOi9nL3BlcnNvbmFsL2NoZW5sZWlfMjAxNl9tYWlsX2hmdXRfZWR1X2NuL0Vscmd0Yy02aS1OSXZlRVBteDlZcWVzQkNTVUM4UWdSaVZuNUlPLVFiSWFheEE_cnRpbWU9UTJxbzBuVGMyRWc)\]



<!-- ## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/newlei/chenlei.github.io/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/newlei/chenlei.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out. -->
