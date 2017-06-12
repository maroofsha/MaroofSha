---
name: Riaz Ahamed
position: Managing Director
external_url: www.maroofsha.github.io/MaroofSha/riaz.html
image_path: "http://i67.tinypic.com/znvia8.png"

---

Not for profit themed template for Jekyll. Browse through a live demo. Increase the web presence of a not for profit or cause website with this configurable theme.

CloudCannon was made by CloudCannon, the Cloud CMS for Jekyll. Find more templates and themes at Jekyll Tips.

Learn Jekyll with step-by-step tutorials and videos at Jekyll Tips.
Features

    Pre-built pages
    Pre-styled components
    Configurable footer
    Optimised for editing in CloudCannon
    SEO tags
    Google Analytics
    Donorbox
    MailChimp

Setup

    Add your site details in _config.yml.
    Add your Google Analytics to _config.yml.
    Get a workflow going to see your site's output (with CloudCannon or Jekyll locally).

Develop

Cause was built with Jekyll version 3.3.1, but should support newer versions as well.

Install the dependencies with Bundler:

$ bundle install

Run jekyll commands through Bundler to ensure you're using the right versions:

$ bundle exec jekyll serve

Editing

Cause is already optimised for updating pages, company details and footer elements in CloudCannon.
SEO Tag

This site uses the jekyll-seo-tag plugin. You should at least set a title in front matter on each page. Have a look at the project page for more options.
Google Analytics

Google Analytics is a third party website analytics tool. To install:

    Add your Google Analytics key to _config.yml
    Run your site in production JEKYLL_ENV=production. This is the default in CloudCannon and GitHub Pages.

Donorbox

Donorbox is a third party embeddable donation form for websites. To install:

    Set up a campaign on Donorbox
    Copy the embed code from the Dashboard screen
    Paste it into donation_embed in the index.html front matter

Mailchimp

Mailchimp is a third party embeddable newsletter for websites. To install:

    Set up a campaign on Mailchimp
    Find the embed code for the sign up form
    Copy the <form>'s action url
    Paste it into newsletter_action in the index.html front matter

Company details

    Reused around the site to save multiple editing locations.
    Set in the Data / Company section.

