# GmodHQ Docs
Documentation and rules for GmodHQ network

## Usage

Clone repo<br />
```
git clone https://github.com/BeefBytes/docs.gmodhq.com.git
```

Start development server. Make sure you're in the same dir as mkdocs.yml<br />
```
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
```

Build docs. Make sure you're in the same dir as mkdocs.yml<br />
```
docker run --rm -it -v ${PWD}:/docs squidfunk/mkdocs-material build
```

## Resources
Mkdocs documentation<br />
https://www.mkdocs.org/

Material for mkdocs documentation<br />
https://squidfunk.github.io/mkdocs-material/

Material for mkdocs docker documentation<br />
https://hub.docker.com/r/squidfunk/mkdocs-material/
