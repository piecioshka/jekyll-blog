# jekyll-blog

Blog example with use of [Jekyll](https://jekyllrb.com/)

## Preview 🎉

https://piecioshka.github.io/jekyll-blog/

## Development

```bash
jekyll serve
# open in browser http://127.0.0.1:4000/
```

## Build

```bash
jekyll clean
jekyll build -b jekyll-blog
```

## Deployment

```bash
rm -rf tmp/
CACHE_DIR=tmp/ npx gh-pages -d _site
```
