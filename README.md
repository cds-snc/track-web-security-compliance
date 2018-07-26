# Track web security compliance documentation

*Track web security compliance* is a web-based application that scans Government of Canada websites and web services and reports on their web security. The application is currently available for Government of Canada employees and can be found at [https-everywhere.canada.ca](https://https.canada.ca). This repository contains companion documentation for the project and can be viewed at [https://cds-snc.github.io/track-web-security-compliance](https://cds-snc.github.io/track-web-security-compliance).

## Editing the documentation

The documentation uses [Jekyll](http://jekyllrb.com/) and the [DOCter](https://github.com/cfpb/DOCter) theme.

DOCter needs Jekyll and other dependencies to run locally. These can be installed with Bundler by running the following commands.

```
gem install bundler
bundle install
```

Run Jekyll:

```
bundle exec jekyll serve --watch --baseurl ''
```

Open it up in your browser: <http://localhost:4000/>


### _config.yml

Options within the `_config.yml` file allow you to control some of the site's
content and left column navigation.
