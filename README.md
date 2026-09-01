# katha-feed

Deploy target for **katha.syahi.sh**. This repo holds nothing but the
generated `feed.xml` and the GitHub Pages `CNAME` — never edit `feed.xml`
here directly, it's overwritten by every publish.

Source of truth, scripts, and the design doc all live in the private
`syahi-labs/katha-audio` repo. Run `./publish_feed.sh` there to update this
one.

Public on purpose: GitHub Pages on the free plan only serves from public
repos, and the deployed feed has to be public regardless — that's what a
podcast feed is for. Splitting the source (private) from the deploy artifact
(public, minimal) keeps everything else — episode drafts, business
reasoning, the design doc — out of public view.
