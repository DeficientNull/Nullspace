# Nullspace

About a year ago i decided i wanted to build my own website, the result was the old defective null domain. To keep it short, the way i was doing stuff there had a lot of issues. So i decided to rewrite it.

## Markdown embedding with `md-block`

A pretty major feature now is that i get to write all my content in markdown, this is made possible by the wonderful md-block element. It features plenty all over the source and this is a great example of how to use it in this kind of project

## Testing caveats

Nullspace is a static site but with `md-block` you'll likely run into an issue when testing it by loading index.html directly into your browser. If you're using a remote link to point to an external markdown file apparently that won't work because of how `md-block` looks for said file in Javascript. This means that the best way to test this is to host a local server. The best one i've found is [Vercel Serve](https://github.com/vercel/serve) it works pretty well out of the box with no configuration required (though you will need to install node/npm)

Unfortunately the author of `md-block` seems to have dropped development so there's no one to really reach out to and actually try to fix this or any other problems that might come up

I'll update this repo if another of these issues comes along.
## Licensing

This project uses the MIT License, check LICENSE.MD for more information


