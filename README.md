# Nødvendigt Forum

### Installation
Install Ruby version 2.5.0
```bash
rvm install 'ruby-2.5.0'
rvm use ruby-2.5.0
```

### Install bundler
```bash
gem install bundler
```

### Install jekyll
```bash
gem install jekyll
```

### Install dependencies
```bash
bundle install
```

### Start server
```bash
jekyll serve --config _config.yml,_config_dev.yml
```

### To add a new blog post
1. Create a new file in `_publications`
2. Insert layout prop, published_date prop, date prop, and pdf_name prop
3. Insert content

### Example of a blog post
```
---
layout: publication
published_date: Oktober 2018
date: 2018-10-01
pdf_name: oktober_2018
---

This is the content
```
