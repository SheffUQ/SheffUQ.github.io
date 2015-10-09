# Editing SheffieldUQ pages

These are the webpages for the SheffieldUQ group.

### Getting started

* Tell me your github name so that I can add you to the SheffUQ group.
* Clone the page
```
git clone https://github.com/SheffUQ/SheffUQ.github.io.git
cd SheffUQ.github.io
```
* Make changes etc.
* Run `jekyll serve` (You must install [jekyll](http://jekyllrb.com/) first).
* Open web browser and enter "http://127.0.0.1:4000/" to see the website.


### Blog entries
* `cd _posts/`
* Create a new file that obeys the naming convention YEAR-MONTH-DATE-NAME.markdown
* ```bash
cd ../
jekyll serve
```


### Updating github

Because we are using [Jekyll-scholar](https://github.com/inukshuk/jekyll-scholar) for the references, updating the pages is slightly convoluted.

There are two branches to the repo - master and source. All the source code lives in the source branch, and the html from the `_site/` directory needs to go into the `master` branch.





### Source
The website uses the [Jekyll-Pithy](https://github.com/smallmuou/Jekyll-Pithy) theme.
