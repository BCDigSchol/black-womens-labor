# black-womens-labor

*Jekyll website for the Black Women's Labor Project @ [Boston College](https://bc.edu)*

By UNCERTAIN

## About

Race has always played a role in work in the United States. The kind of work available to you, the ways you were able to complete that work, and how your community viewed the work you did, all intersect with race. The end of the plantation system of slavery in the Southern US did not fundamentally change how Americans thought about race. Whether in the North or South, race continued to be a factor in what kinds of work were available to any individual, as well as how much they were paid for it.

Gender, similarly, has also always been a factor in labor. “Women’s work” has taken various forms throughout US history, often being separated from men’s work by arbitrary cultural factors and societal limitations. Women’s work has also been historically undervalued and underpaid in comparison to traditionally male occupations. Work is also not limited to paid jobs outside the home. Domestic work within one’s household is a form of work, though rarely recognized as such.

This is not a complete record of Black women’s census responses in 1920 Boston, but this representative sample of women between the ages of 20-30 can help shed some light on what possibilities of work were possible for Black women. The stories of individual women included here, though filtered through official records and government data, can hopefully give the readers some insight into the lives of these women and the cultural norms that shaped their work opportunities.

## Local Development

* Follow [this guide](https://jekyllrb.com/docs/installation/) to install Ruby and Jekyll
* Install [Node](https://nodejs.org/en)
* `git clone` this repo and then `cd` inside the directory
* Comment out the `url` and `baseurl` lines of `_config.yml` when working locally
* Install Ruby dependencies by running `bundle install`
* Install Node dependencies by running `npm install`
* Run the server with `bundle exec jekyll serve`

## How to Make Changes

**To set attribution**

``` bash
README.md # this file, make sure to change with your name in the credits
CITATION.cff # the citation file, make sure to include your project name and author(s) names. Use OrcIDs if you have them
package.json # the npm package file, include the project title and author information (again)
_config.yml # the Jekyll config file, which controls how the page is put together, include project name, author names, project locations, and footer messages
```

**To change the theme**

``` bash
_sass/theme-settings.scss # edit this file to change theme colors, fonts, and the sizes of the headers/footers
_sass/custom-style.scss # edit this file to add your CSS (or SCSS) to the site. CSS here will override other files
_sass/theme.scss # advanced, contains the code for the theme itself, edit to customize the theme directly
```

**To change the site structure (the nav menu)**

```bash
_config.yml # the Jekyll config file, edit the section titled nav-menu. Note that you can nest menus using a submenu attribute
_pages/ # where you create individual site pages (either .html or .md). As you change the _config.yml you should create new files here, or rename/delete existing ones, to match _config.yml
```

**To use built-in TailwindCSS**

```bash
https://tailwindcss.com/docs # tailwind is already installed, consult the docs to look up how to use it for things like flex layout, margins, alignment, and more
```

``` html
<!-- example of a tailwindcss element that goes to width 100% and also centers the text inside-->
<div class="w-full text-center">Some text</div>
```

## Acknowledgements

Jekyll & Tailwind Setup based on [TailPages](https://github.com/harrywang/tailpages) by [Harry Wang](https://harrywang.me/) (Chinese: 王建楠)