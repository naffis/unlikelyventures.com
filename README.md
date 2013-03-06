# Unlikely Ventures Landing Page

This is the landing page for Unlikely Ventures. It's just a static
HTML site served up via Jekyll and Jekyll S3.

## Installation

```
bundle install
```

## Deploying

To deploy, you will need to copy `_jekyll_s3.yml.example` to 
`_jekyll_s3.yml` and supply an AWS ID and secret in that file.
Once you've done so you may deploy simply by running:

```
bundle exec jekyll && bundle exec jekyll-s3
```