# eScienceLab.github.io
draft website for eScience Lab, Jekyll and GitHub Pages

See the [Jekyll documentation](http://jekyllrb.com/docs/home/)

* Pages are edited in [MarkDown](https://daringfireball.net/projects/markdown/)
 * See also various Jekyll's documentation on [writing posts](http://jekyllrb.com/docs/posts/) and [writing pages](http://jekyllrb.com/docs/pages/)
* You can edit directly in GitHub web interface, or use `git` and your favourite editor
* Edited pages are published automatically by GitHub after a few minutes.
* For extensive changes or debugging, you might want to `git clone` this repository and run [Jekyll](http://jekyllrb.com/) locally to test your changes and see debug outputs.
  * Test locally with Docker image jekyll/jekyll:pages:
  
      `docker run -it --rm --name jekyll --volume=$(pwd):/srv/jekyll -p 4000:4000 jekyll/jekyll:pages`

