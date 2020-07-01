# PyLadies Chicago Website

PyLadies Chicago website is powered by Netlify using the [PyLadies Netlify website template](https://github.com/pyladies/netlify-website-template/). The page is hosted via GitHub pages.

The PyLadies Chicago chapter is organized by [Lorena Mesa](https://github.com/lorenanicole) and Sand Ip.

## Setting up you website with Netlify

1. Fork the repo.
2. We advise replacing `master` with `main` as the [default branch](https://docs.github.com/en/github/administering-a-repository/setting-the-default-branch). 
3. Register for a Netlify account. [Open source teams qualify for free OSS accounts](https://www.netlify.com/legal/open-source-policy/), use your `pyladies` chapter email address when creating your account. You'll need to host a Netlify badge on your website which is already included in the emplate. Please note that any overages will be additionally charged.
4. Setup your site with [these directions](https://www.netlify.com/blog/2016/10/27/a-step-by-step-guide-deploying-a-static-site-or-single-page-app/). As this is a simple html and css website there is no need for custom build steps.
4. If you have requested a [custom domain](https://github.com/pyladies/pyladies/README.md) you can configure that within [your Netlify site](https://www.netlify.com/blog/2020/03/26/how-to-set-up-netlify-dns-custom-domains-cname-a-records/).

## Local Development

If you'd like to see your changes locally you can use `Python3` to serve up the content by:

```bash
$ cd /root-of-forked-directory
$ python -m http.server # Defaults to port 8000, you can change by providing an additional integer for the desired port
```

## Hosting your website on GitHub pages

GitHub provides a free hosted page for each [GitHub user](https://pages.github.com/) available at `github_username.github.io`. The custom domain is defined in the `CNAME` file.

## Questions?

Ask for help in the [PyLadies Slack](slackin.pyladies.com) in the `#project-tech-infra` channel. Or contact `chicago@pyladies.com`.

## Acknowledgements

[PyLadies NYC](http://nyc.pyladies.com/) created this theme initially, thank you!
