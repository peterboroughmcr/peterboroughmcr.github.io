# Github Pages site for Peterborough Model Car Racing Club (PMCR)

Peterborough Model Car Racing Club (PMCR) is a radio control racing club based in Peterborough, UK. PMCR wanted to create a [website](https://peterboroughmcr.github.io) for the club and decided to use GitHub Pages. 

# Github Pages help for editors

GitHub Pages is a service that turns [Markdown](https://www.markdownguide.org/tools/github-pages/) files into a website and hosts them for free on the internet. GitHub Pages uses the [Jekyll](https://jekyllrb.com) static site generator to generate webpages from Markdown files.

What is Markdown? Markdown is a lightweight markup language that you can use to add formatting elements to text documents. Note that GitHub Pages uses its own flavour of Markdown.

## Jekyll Links

From [Mastering Jekyll, URLs and links in Jekyll](https://mademistakes.com/mastering-jekyll/how-to-link/)

Link to a page, here is an example Truck link to content for a file `racingclasses.markdown`. Note the `.markdown` extension is included  
```
[Truck]({% link racingclasses.markdown %})
```

Linking posts, here is an example Results link to content for a file `_posts/2025-01-11-results.markdown`. Note the `.markdown` extension is **not** included  
```
[Results]({% post_url 2025-01-11-results %})
```