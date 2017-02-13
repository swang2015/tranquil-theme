# tranquil-theme

A stylish jekyll theme from my blog.

## features

- Responsive design
- MathJax mathematics with Latex notation
- Comment threads
- Pagination
- Browsing by categories/tags
- Archive: posts timeline
- Homepage slider of feature posts
- Blog widgets
- Back to top button
- Vintage style

## usage

- add social username in `_data/social.yaml`
- assign ONE category for each post
- add `feature` into tags if you want to show post at homepage slider
- if MathJax is enabled, use `$$...$$` and `\[...\]` for displayed mathematics, and `\(...\)` for in-line mathematics

### site configurations

| Variable | Description |
| --- | --- |
| paginate | posts per pagination |
| disqus_forumname | create an site on disqus and put the name here |

### post configurations

| Variable | Description |
| --- | --- |
| background | image relative path |
| category | put ONE category |
| tags | a list of tags |
| math | set `true` or `false` to enable MathJax mathematics |
