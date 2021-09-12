# Lexicon

A Standard for describing the meaningful units and vocabulary of your Terra, Cosmos or any IBC-enabled projects

## What is Lexicon?

Really this is just an MkDocs template, but every project needs a cool name to get funding.

**Lexicon** is a simple template you can use to setup a hosted docs portal for your project, all for free using Github Pages.

I started this project as I seen more and more projects using Gitbooks which used to be a static site generator also but as of late has moved towards Docs as a Service.
Instead this project is offered to you for free at no charge, not now, not later and especially not as your team grows. Rather than prey on your success I simply want to make documentation better and more standard across the space.

## Using Custom Assets

Using your projects own theming, logos and favicons is important and so below is a quick example of this.

In your `mkdocs.yml` this piece of Yaml will be relevant
```yaml
# Theme
theme:
  icon:
    logo: mylogo
  favicon: favicon.png
  custom_dir: override
```

Above you will see an override of the logo and the favicon using an SVG logo and a PNG icon. All that is needed with the above is the `custom_dir` which tells mkdocs where to look for these files.
