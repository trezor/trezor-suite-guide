# Guide for writers

## How to write

Contents of this GitBook are packaged into Suite by a custom script that is based on a few assumptions about structure of the content.

### Groups are for locales

We support localization of the content by having a group for each locale. The groups should be named by corresponding  [ISO 639-1 2-letter code.](https://www.wikiwand.com/en/List\_of\_ISO\_639-1\_codes)

Localised variants of a single page are paired by the **slugs** which can be set in the "three dot" menu of each page. For nested pages the slugs must match on all levels.\
\
For example, if you want to write a czech translation for english page with slug `bitcoin` that is under a page with slug `coins` you must create a group named `cs` containing a page with slug `coins` containing a page with slug `bitcoin`. Only then it will be recognised as a translation of the english page. The title and the content can be altered freely.

### English is the canonical version

English locale defines the content structure. All other locales can only provide translations of english pages but they can't define their own pages.

This means that any non-english page that doesn't have a slug matching slug of some english page won't be displayed in Suite.

### Categories can't hold content

**Categories are pages that have sub-pages**. We do not allow categories to hold content on their own. Categories only serve to organise the content which must be put in leaf pages -- that is pages without children.

### Not all types of rich content are supported

As of now only these elements are supported:

![](.gitbook/assets/readme\_features\_info.png)

### Images

* To add an image to root categories, just add corresponding images to their content without any caption or additional text.
* To add images to articles, just add corresponding images to content without any caption. Please be aware that guide content width is only 305px.
* Make sure not to have duplicate images or files. Github renames duplicates to contain parentheses and that breaks images in all articles.&#x20;
* Do not use parentheses, spaces or special characters in image files names.&#x20;

Please delete unused images. Otherwise, they are unnecessarily bundled with the application.

## How to publish

The contents of this GitBook are packaged with each release of Suite application. The version is controlled from within Suite's codebase via the `GITBOOK_REVISION` constant in the `suite-data` package. After data sync from the GitBook platform to this repo, a GitHub action to update the constant in Suite is triggered. Once the pipeline finishes, you can check the result in Suite [dev environment](https://suite.corp.sldev.cz/suite-web/chore/update-suite-guide/web/). If the GitBook content was synced to the `master` branch of this repository, a pull request is automatically created in the Suite repo to be checked by the devs and to make its way into production with the next release.

## Testing in Suite

Sometimes, you might want to see your changes in Suite UI without publishing them. The process is the same as publishing, but the GitBook project must sync into the `develop` branch instead of `master` so that it does not create a pull request.