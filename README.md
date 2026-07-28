# biohack-me.github.io

This is the homepage of [biohack.me](http://biohack.me), which directs users to the different components of the site.

It uses the [Jekyll](http://jekyllrb.com) static site builder, and is hosted on GitHub pages. Commits to the master branch of this repository will be immediately visible on [biohack.me](http://biohack.me).

## Development

To run this site on your own computer, you will need a recent version of the Ruby programming language.

After cloning this repository, run:

```bash
gem install bundler  # only required if bundler isn't already installed
bundle install
jekyll server
```

The development site should now be available at `http://localhost:4000`.

This repo is set up with a pre-commit secret scanning check, so before committing any changes you should install [betterleaks](https://github.com/betterleaks/betterleaks) locally, as well as [pre-commit](https://pre-commit.com/), and enable the pre-commit task with:
```bash
pre-commit install
```

## Contributing

1. [Fork](https://github.com/biohack-me/biohack-me.github.io/fork) this repository
2. Clone your forked repository
3. Commit your changes
4. Open a [Pull Request](https://github.com/biohack-me/biohack-me.github.io/compare)