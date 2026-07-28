# wi-chiba.github.io
Public web site for Wisconsin-Chiba, Inc.


## Local Development
To build and serve the site locally to view changes, run the following:

```bash
$ hugo server
```

Point your web browser at [http://127.0.0.1:1313/](http://127.0.0.1:1313/).

## Source Files

* `assets`: Static content like images, CSS, and Javascript includes
* `config`: Configuration files for Hugo, contact info in the footer, and the links in the navigation bar.
* `content`: Contains content of pages except the index page.  One Markdown (.md) file per page.
* `data`: The index page is built from 4 components:
  * `clients`: Showcases clients with blurbs and and their company logos.  This is currently disabled.
  * `features`: Showcases product features or case studies.  Currently disabled.
  * `highlights`: Similar to the features.  I have this enabled.
  * `hero`: Controls the top banner with text (left), a large image (right), a button link, and bullet points.
