![SnapReads icon](static/icon.png)
# SnapReads
Collaborative repository to store and easily share infographics summaries of books, conference talks, articles, concepts…
## Getting started
The website is based on [Hugo](https://gohugo.io) and use the [Blowfish theme](https://blowfish.page)

To start the website locally, on will first need to [install Hugo](https://gohugo.io/installation/). 

Start the live server from the root directory with
```sh
hugo serve
```

# Contributing
If you want to contribute, simply clone the repo and push in a dedicated branch.

## Create infographics
Visual summaries are a very good way to share knowledge and spread ideas. So it might be good idea to turn your favorite book into a graphic form to encourage people exploring it.

[Yoan Thirion](https://www.yoan-thirion.com/#home) wrote an article on [How to make book infographics](https://yoan-thirion.gitbook.io/knowledge-base/xtrem-reading/how-to-make-book-infographics). It is a great starting point if you want to start making one.

## Publish infographics
The point of this website is to concentrate infographics for different materials, so you are more than welcome to contribute if you make such summaries and are willing to share them.

If you want to share something you did not create, please make sure that the license allows it, and/or that the author agrees to it.

### Add New Author
The author here is the person who made the infographic, not the author of the source material.

You need two elements to create an author card:

 * An avatar for the author (photography or avatar)
 * The author data

The avatar must be placed in the [assets/img/authors](assets/img/authors). Any format is ok, just make sure it looks good in a circle and doesn't take too long to load.

For the data, simply duplicate the template file from [templates/authors](templates/authors/John%20Doe.json) and place it in the [data/authors/](data/authors) folder. Name the file with the real name of the author, as it will be used in some part of the website.

You may do your personal promotion here. You can add as many link in the social section as you want. The keys in the array can be any icon name from the [icons list](https://blowfish.page/samples/icons/).

### Add New Infographic
Once the author is added, you can publish your infographic.
#### The source material hasn't any infographic

Create a folder in [content/infographics](content/infographics), named after your source. You can copy an existing folder or the template folder in [templates/infographics](templates/infographics).

Your folder must contain 3 elements:

##### 1. The pdf or the image of your infographics
Higher resolution is better

##### 2. The "featured.png" image
 You can take a part of the infographics as a capture. This image will appear in the infographics listing.

##### 3. The index.md 
The main article. Please at least set the title, date, authors and tags.

Limit the tags to 5 maximum. Try to reuse existing ones if applicable. The first one should be the type of your source material: book, talk, idea, video, ...

You can add relevant links, some info, but the infographics is the main piece, so don't add too much. 

#### Another infographic for the source material already exist

Add your infographics to the existing folder. Edit the index.md to add the second version and another author.

## Other contributions
Other contributions are welcome, feel free to do one if you think it can enhance the website :)