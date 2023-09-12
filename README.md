# Replica [![LICENSE MIT](https://img.shields.io/badge/LICENSE-MIT-blue.svg)](https://opensource.org/licenses/MIT)
Github style replication for hexo theme. 

Because we love octocat! :two_hearts:
[Click here to view the demo site](//lispking.github.io/tech)

Issues & Contributions are welcome! :stuck_out_tongue:

## Version
#### v1.0
Github UI in 2023, which uses the black navbar

## Setup
#### Install
```
git clone https://github.com/lispking/hexo-theme-replica.git themes/replica
```

#### Configure
Set `theme: replica` in `_config.yml` (the one in your root folder)

**PLEASE NOTE** 
Modifying `blog_root/themes/replica/_config.yml` directly is **NOT** recommended.  
It's suggested to configure your site through `blog_root/_config.yml` **(root folder).**

Here is a sample of `blog_root/_config.yml`
<details>
<summary>CLICK ME</summary>
<p>

``` yml
# Hexo Configuration
## Docs: http://hexo.io/docs/configuration.html
## Source: https://github.com/hexojs/hexo/

# Site
title: My Blog
description: My Blog Description
author: HiiTea
language: zh-CN
timezone: Asia/Shanghai
favicon: https://assets-cdn.github.com/favicon.ico

# URL
## If your site is put in a subdirectory, set url as 'http://yoursite.com/child' and root as '/child/'
url: http://lispking.github.io/tech
root: /tech/
permalink: :year/:month/:day/:title/
permalink_defaults:

# Directory
source_dir: source
public_dir: public
tag_dir: tags
archive_dir: archives
category_dir: categories
code_dir: downloads/code
i18n_dir: :lang
skip_render:

# Writing
new_post_name: :year:month:day-:title.md # File name of new posts
default_layout: post
titlecase: false # Transform title into titlecase
external_link: true # Open external links in new tab
filename_case: 0
render_drafts: false
post_asset_folder: false
relative_link: false
future: true
highlight:
  enable: true
  line_number: true
  auto_detect: false
  tab_replace:

# Category & Tag
default_category: uncategorized
category_map:
tag_map:

# Date / Time format
## Hexo uses Moment.js to parse and display date
## You can customize the date format as defined in
## http://momentjs.com/docs/#/displaying/format/
date_format: YYYY-MM-DD
time_format: HH:mm:ss

# Pagination
## Set per_page to 0 to disable pagination
per_page: 0
pagination_dir: page

# Extensions
theme: replica

# Google Analytics
ga: # GA code UA-XXXXXXXX-X

#marked setting for markdown
marked:
  gfm: true
  pedantic: false
  sanitize: false
  tables: true
  breaks: true
  smartLists: true
  smartypants: true

gcs: # GOOGLE CUSTOM SEARCH
baidutongji: # BAIDU TONGJI CODE
disqus: # DISQUS ID

location: Hong Kong
email: xx@example.com

avatar: https://avatars.githubusercontent.com/u/4446580?v=4
social:
  github: https://github.com/lispking

# flagcounter
flagcounter_href: # https://info.flagcounter.com/xxxx
flagcounter_img_src: # https://s01.flagcounter.com/xxxx
```

#### Update
``` bash
cd themes/replica
git pull
```

In case you want the old version with grey navbar
``` bash
cd themes/replica
git checkout 1.0 # AKA `git checkout -b 1.0 origin/1.0`
```
</p>
</details>

## Available Widgets
百度统计  
Disqus  
Google Analytics  
Google Custom Search Engine[^1]

## FAQ
#### Q: How can I use category and tag?
A: Create below files under `source` folder:

`blog_root/source/categories/index.md`:

```
---
title: categories
date: 2016-01-21 18:46:15
---
```

`blog_root/source/tags/index.md`:

```
---
title: tags
date: 2016-01-21 18:45:55
---
```

## License
The MIT License[^2]

[^1]: https://cse.google.com/
[^2]: https://opensource.org/licenses/MIT

## Buy me coffee :yum:
ETH: 0x8179dEb7e60c5120690132615b3f569c88D92e08  

![PayCode](images/paycode.png)
