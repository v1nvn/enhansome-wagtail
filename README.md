# Awesome Wagtail [![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 436,589 | 🐛 68 | 📅 2026-01-28 [<img src="https://cdn.jsdelivr.net/gh/springload/awesome-wagtail@ac912cc661a7099813f90545adffa6bb3e75216c/logo.svg" width="104" align="right" alt="Wagtail">](https://wagtail.org/) with stars

> A curated list of awesome packages, articles, and other cool resources from the Wagtail community.
> [Wagtail](https://wagtail.org/) is a Python CMS powered by Django, focusing on flexibility and user experience.

*You might also like [Awesome Django](https://github.com/wsvincent/awesome-django) ⭐ 10,967 | 🐛 1 | 🌐 Python | 📅 2026-01-29 and [Awesome Python](https://github.com/vinta/awesome-python) ⭐ 282,312 | 🐛 16 | 🌐 Python | 📅 2026-02-10. :snake:*

## Contents

* [General resources](#general-resources)
* [Apps](#apps)
  * [Blogging/news](#bloggingnews)
  * [Rich text editor extensions](#rich-text-editor-extensions)
  * [Widgets](#widgets)
  * [StreamField](#streamfield)
  * [Static site generation](#static-site-generation)
  * [Settings management](#settings-management)
  * [E-commerce](#e-commerce)
  * [SEO and SMO](#seo-and-smo)
  * [Analytics](#analytics)
  * [Customer experience](#customer-experience)
  * [Security](#security)
  * [Media](#media)
  * [Translations](#translations)
  * [Forms](#forms)
  * [Testing](#testing)
  * [Modeladmin](#modeladmin)
  * [Asynchronous (tasks)](#asynchronous-tasks)
  * [Content Management](#content-management)
  * [Misc](#misc)
* [Tools](#tools)
  * [Templates & Starter Kits](#templates--starter-kits)
* [Resources](#resources)
  * [Getting started](#getting-started)
  * [Articles](#articles)
  * [Recipes](#recipes)
  * [Presentations](#presentations)
  * [Podcasts](#podcasts)
  * [Videos](#videos)
  * [Books](#books)
  * [Showcases](#showcases)
  * [Lists](#lists)
* [For editors](#for-editors)
* [Community](#community)
* [Open-source sites](#open-source-sites)

## General resources

* [Official site](https://wagtail.org/)
* [GitHub repository](https://github.com/wagtail/wagtail) ⭐ 20,132 | 🐛 1,006 | 🌐 Python | 📅 2026-02-10
* [Twitter account](https://x.com/wagtailcms)
* [Roadmap](https://wagtail.org/roadmap/)
* [PyPI classifiers for Wagtail](https://pypi.org/pypi?%3Aaction=list_classifiers)
* [Other resources](#resources)

## Apps

### Blogging/news

* [wagtailnews](https://github.com/neon-jungle/wagtailnews) ⭐ 75 | 🐛 4 | 🌐 Python | 📅 2023-12-20 - A plugin for Wagtail that provides news / blogging functionality.
* [Django Wagtail Feeds](https://github.com/chrisdev/django-wagtail-feeds) ⭐ 61 | 🐛 7 | 🌐 Python | 📅 2022-12-26 - Add support for RSS Feeds, Facebook Instant Articles and Apple News Publisher to your Wagtail CMS Projects.
* [wagtail-blog-app](https://github.com/Tivix/wagtail-blog-app) ⭐ 39 | 🐛 5 | 🌐 Python | 📅 2016-08-18 - A blog application for the Wagtail Django CMS.
* [wagtail-live](https://github.com/wagtail/wagtail-live) ⭐ 37 | 🐛 15 | 🌐 Python | 📅 2022-03-21 - Build live blogs with Wagtail.
* [Snotra\_RSS](https://github.com/olopost/snotra_rss) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2021-01-09 - Snotra\_RSS is an Atom and RSS news aggregator app for Wagtail.
* [Puput](https://puput.readthedocs.io/en/latest/) - Puput is a powerful and simple Django app to manage a blog. It uses the awesome Wagtail CMS as content management system.
* [wagtail\_blog](https://gitlab.com/thelabnyc/wagtail_blog) - A WordPress-like blog app implemented in Wagtail.

### Rich text editor extensions

* [Wagtail TinyMCE](https://github.com/isotoma/wagtailtinymce) ⚠️ Archived - A TinyMCE editor integration for Wagtail.
* [wagtailembedder](https://github.com/springload/wagtailembedder) ⭐ 37 | 🐛 1 | 🌐 Python | 📅 2023-02-08 - Snippets embedder for Wagtail richtext fields.
* [WagtailDraftail](https://github.com/springload/wagtaildraftail) ⭐ 24 | 🐛 20 | 🌐 Python | 📅 2017-11-08 – Draft.js editor for Wagtail, built upon [Draftail](https://github.com/springload/draftail) ⭐ 631 | 🐛 31 | 🌐 TypeScript | 📅 2025-09-29 and [draftjs\_exporter](https://github.com/springload/draftjs_exporter) ⭐ 83 | 🐛 3 | 🌐 Python | 📅 2026-01-24.
* [Wagtail Medium Editor](https://github.com/dperetti/Django-wagtailmedium) ⭐ 18 | 🐛 6 | 🌐 Python | 📅 2021-05-09 - A customizable Medium Editor for Wagtail, with link anchors support.
* [wagtail-readability](https://github.com/neon-jungle/wagtail-readability) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2016-03-08 - Test how readable the content you enter into Wagtail is.
* [Wagtail Froala](https://github.com/jaydensmith/wagtailfroala) ⚠️ Archived - Extends Wagtail to use the Froala WYSIWYG editor in RichTextField/RichTextBlock.
* [Wagtail EditorJS](https://github.com/Nigel2392/wagtail_editorjs) ⭐ 13 | 🐛 3 | 🌐 Python | 📅 2025-03-06 - An [EditorJS](https://editorjs.io/) widget with great support for Wagtail's page, image and document choosers.
* [Wagtail Terms](https://github.com/smark-1/wagtailterms) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2026-02-09 - A plugin to add a glossary terms entity to the Draftail editor.
* [Wagtail Text Alignment](https://github.com/Nigel2392/wagtail_text_alignment) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2024-05-13 - Align text, headings and more in your Wagtail richtext editor.
* [wagtailmdx](https://github.com/julinodev/wagtailmdx) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2024-09-27 - A [MDXEditor](https://github.com/mdx-editor/editor) ⭐ 3,237 | 🐛 87 | 🌐 TypeScript | 📅 2025-12-24 integration for Wagtail as textfield widget.

### Widgets

* [wagtail-markdown](https://github.com/torchbox/wagtail-markdown) ⭐ 215 | 🐛 13 | 🌐 Python | 📅 2026-01-05 - Markdown fields and blocks for Wagtail.
* [Wagtail-Geo-Widget](https://github.com/Frojd/wagtail-geo-widget) ⭐ 147 | 🐛 7 | 🌐 Python | 📅 2025-11-09 - Google Maps widget for the GeoDjango PointField field in Wagtail.
* [wagtail-autocomplete](https://github.com/wagtail/wagtail-autocomplete) ⭐ 129 | 🐛 52 | 🌐 Python | 📅 2025-07-30 - Autocompleting choosers for `ForeignKey`, `ParentalKey`, and `ManyToMany` fields.
* [wagtail-generic-chooser](https://github.com/wagtail/wagtail-generic-chooser) ⭐ 117 | 🐛 14 | 🌐 Python | 📅 2025-06-06 - provides base classes for building chooser popups and form widgets for the Wagtail admin, matching the look and feel of Wagtail's built-in choosers for pages, documents, snippets and images.
* [wagtailgmaps](https://github.com/springload/wagtailgmaps) ⭐ 83 | 🐛 10 | 🌐 Python | 📅 2025-06-17 - Simple Google Maps address formatter for Wagtail fields.
* [wagtail-color-panel](https://github.com/marteinn/wagtail-color-panel) ⭐ 56 | 🐛 2 | 🌐 Python | 📅 2025-11-23 - Introduces panels for selecting colors in Wagtail.
* [wagtail-instance-selector](https://github.com/ixc/wagtail-instance-selector) ⭐ 55 | 🐛 7 | 🌐 Python | 📅 2025-09-12 - A `ForeignKey` widget to create and select related items. Similar to Django's `raw_id_fields`.
* [wagtail-leaflet-widget](https://github.com/icpac-igad/wagtail-leaflet-widget) ⭐ 23 | 🐛 3 | 🌐 Python | 📅 2022-05-13 - A Leaflet JS - OSM based wagtail geo-location widget.
* [wagtail-multi-upload](https://github.com/spapas/wagtail-multi-upload) ⭐ 19 | 🐛 2 | 🌐 JavaScript | 📅 2023-05-03 - allows uploading of multiple related images for a page.
* [Wagtail Ace Editor](https://github.com/Nigel2392/wagtail_ace_editor) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2024-07-09 - An IDE-like code editor right in your Wagtail admin.
* [Wagtail HTML Editor](https://github.com/kkm-horikawa/wagtail-html-editor) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2026-01-26 - A CodeMirror 6-powered HTML editor for Wagtail with syntax highlighting, Emmet support, and dark mode.

### StreamField

* [Wagtail Code Block](https://github.com/wagtail-nest/wagtailcodeblock) ⭐ 170 | 🐛 5 | 🌐 Python | 📅 2025-12-19 - StreamField code blocks for the Wagtail CMS with real-time PrismJS Syntax Highlighting.
* [Wagtail Blocks](https://github.com/ibrahimawadhamid/wagtail_blocks) ⭐ 82 | 🐛 2 | 🌐 HTML | 📅 2024-05-16 - A Collection of awesome Wagtail CMS stream-field blocks and Charts.
* [wagtail-inventory](https://github.com/cfpb/wagtail-inventory) ⭐ 63 | 🐛 3 | 🌐 Python | 📅 2025-11-07 - Search Wagtail pages by the StreamField blocks they contain.
* [Wagtail Commonblocks](https://github.com/springload/wagtailcommonblocks) ⚠️ Archived - Common StreamField blocks for Wagtail.
* [Wagtail ClearStream](https://github.com/hminnovation/wagtailclearstream) ⭐ 35 | 🐛 8 | 🌐 CSS | 📅 2019-12-16 - An app to make Wagtail's StreamField more modular.
* [UWKM Streamfields](https://github.com/UWKM/uwkm_streamfields) ⭐ 33 | 🐛 4 | 🌐 CSS | 📅 2017-11-01 – A basic set of Wagtail StreamField blocks for fun and profit.
* [Wagtail UIKit Block](https://github.com/kpsaurus/wagtail-uikitblocks) ⭐ 18 | 🐛 1 | 🌐 Python | 📅 2022-12-08 - A collection of UIKit components that can be used as a Wagtail StreamField block.
* [Wagtail SVGmap](https://github.com/City-of-Helsinki/wagtail-svgmap) ⚠️ Archived - ImageMap functionality for Wagtail through inline SVGs.
* [Wagtail Cache Block](https://github.com/AccordBox/wagtail_cache_block) ⭐ 7 | 🐛 3 | 🌐 Python | 📅 2022-12-26 - A templatetag which add HTML fragment cache to your StreamField block
* [Wagtail FontAwesome](https://gitlab.com/alexgleason/wagtailfontawesome) - Add FontAwesome icons to StreamField.

### Static site generation

* [Wagtail-bakery](https://github.com/wagtail-nest/wagtail-bakery) ⭐ 193 | 🐛 20 | 🌐 Python | 📅 2025-01-02 - A set of helpers for baking your Django Wagtail site out as flat files.
* [Wagtail-Netlify](https://github.com/tomdyson/wagtail-netlify) ⭐ 83 | 🐛 7 | 🌐 Python | 📅 2022-05-04 - Easily publish your statically rendered Wagtail site to Netlify.
* [wagtail-freezer](https://github.com/gasman/wagtail-freezer) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2022-06-28 - Generates static HTML sites from a Wagtail project.

### Settings management

* [Wagtail-Flags](https://github.com/cfpb/wagtail-flags) ⭐ 87 | 🐛 2 | 🌐 Python | 📅 2025-11-19 - Feature flags for Wagtail sites.
* [Wagtail-Constance](https://github.com/MechanisM/wagtail-constance) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2022-06-03 - django-constance integration for Wagtail CMS.
* [Wagtail-Waffle](https://github.com/TheCodingSheikh/wagtail-waffle) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2024-03-22 - Manage Django Waffle in Wagtail.

### E-commerce

* [django-salesman](https://github.com/dinoperovic/django-salesman) ⭐ 423 | 🐛 9 | 🌐 Python | 📅 2025-09-24 - Headless e-commerce framework for Django with Wagtail modeladmin integration.
* [longclaw](https://github.com/longclawshop/longclaw) ⭐ 400 | 🐛 46 | 🌐 Python | 📅 2023-08-13 - A shop template for Wagtail CMS.
* [django-oscar-wagtail](https://github.com/LabD/django-oscar-wagtail) ⭐ 106 | 🐛 7 | 🌐 Python | 📅 2022-01-28 - Wagtail integration for Oscar Commerce (or Oscar Commerce integration for Wagtail?).
* [wagtailinvoices](https://github.com/LiamBrenner/wagtailinvoices) ⭐ 34 | 🐛 0 | 🌐 Python | 📅 2017-03-05 - A Wagtail module for creating invoices.

### SEO and SMO

* [wagtail-metadata](https://github.com/neon-jungle/wagtail-metadata) ⭐ 123 | 🐛 4 | 🌐 Python | 📅 2023-09-07 - A tool to assist with metadata for social media and search engines.
* [Wagtail SEO](https://github.com/coderedcorp/wagtail-seo) ⭐ 84 | 🐛 12 | 🌐 Python | 📅 2025-07-11 - Search engine and social media optimization for Wagtail.
* [wagtail-schema.org](https://github.com/neon-jungle/wagtail-schema.org) ⭐ 76 | 🐛 5 | 🌐 Python | 📅 2025-11-26 - Schema.org JSON-LD tags for Wagtail sites.
* [wagtail-metadata-mixin](https://github.com/bashu/wagtail-metadata-mixin) ⭐ 49 | 🐛 3 | 🌐 Python | 📅 2023-06-04 - OpenGraph, Twitter Card and Google+ snippet tags for Wagtail CMS pages.
* [wagtail-opengraph-image-generator](https://github.com/candylabshq/wagtail-opengraph-image-generator) ⭐ 42 | 🐛 2 | 🌐 Python | 📅 2023-10-04 - Assists you in automatically creating Open Graph images for your Wagtail pages.
* [wagtail-meta-preview](https://github.com/Frojd/wagtail-meta-preview) ⭐ 37 | 🐛 6 | 🌐 Python | 📅 2025-03-14 - Adds ability to get share previews for Facebook, Twitter and Google in the Wagtail admin.
* [Wagtail Yoast](https://github.com/Aleksi44/wagtailyoast) ⭐ 36 | 🐛 5 | 🌐 Python | 📅 2025-09-10 - A tool to improve readability of your texts with SEO recommendations.
* [wagtail-redirect-importer](https://github.com/Frojd/wagtail-redirect-importer) ⚠️ Archived - Your friendly neighborhood importer that lets you import redirects from different tabular data formats, such as .csv and .xls

### Analytics

* [Wagtail Analytics](https://github.com/tomdyson/wagalytics) ⭐ 223 | 🐛 30 | 🌐 Python | 📅 2023-01-06 - A Google Analytics dashboard in your Wagtail admin.

### Customer experience

* [Wagtail Personalisation](https://github.com/wagtail-nest/wagtail-personalisation) ⭐ 126 | 🐛 55 | 🌐 Python | 📅 2026-01-27 - Personalisation module, enabling editors to create customised pages - or parts of pages - based on segments whose rules are configured directly in the admin interface.
* [Wagtail Experiments](https://github.com/torchbox/wagtail-experiments) ⭐ 108 | 🐛 9 | 🌐 Python | 📅 2025-12-16 – A/B testing for Wagtail.

### Security

* [wagtail-2fa](https://github.com/labd/wagtail-2fa) ⭐ 90 | 🐛 28 | 🌐 Python | 📅 2026-01-06 - Add two-factor authentication to Wagtail by integrating it with django-otp.
* [wagtailenforcer](https://github.com/springload/wagtailenforcer) ⭐ 47 | 🐛 6 | 🌐 Python | 📅 2022-03-01 - If you need to enforce security protocols on your Wagtail site you've come to the right place.
* [wagtail-yubikey](https://github.com/ahopkins/wagtail-yubikey) ⭐ 7 | 🐛 0 | 🌐 HTML | 📅 2016-04-28 - Enable YubiKey two factor authentication on Wagtail admin panel.

### Media

* [wagtailmedia](https://github.com/torchbox/wagtailmedia) ⭐ 248 | 🐛 26 | 🌐 Python | 📅 2026-01-05 - A Wagtail module for managing video and audio files within the admin.
* [Wagtail Alt Generator](https://github.com/marteinn/wagtail-alt-generator) ⭐ 83 | 🐛 7 | 🌐 Python | 📅 2021-07-16 - A module for generating image description and tags based on computer vision.
* [Rent Free Media](https://github.com/RentFreeMedia/rentfreemedia) ⭐ 81 | 🐛 4 | 🌐 Python | 📅 2023-09-02 - A media distribution framework built on Django and Wagtail. Premium / subscription-based publishing like Patreon or Substack.
* [Wagtail-Textract](https://github.com/fourdigits/wagtail_textract) ⭐ 34 | 🐛 14 | 🌐 Python | 📅 2023-10-25 - Make Wagtail search Documents contents (PDF, Excel and Word, etc.).
* [Wagtail SVG](https://github.com/Aleksi44/wagtailsvg) ⭐ 34 | 🐛 5 | 🌐 Python | 📅 2025-04-19 - A Wagtail module for managing SVG files within the admin.
* [Wagtail-Lazyimages](https://github.com/ptrck/wagtail-lazyimages) ⭐ 23 | 🐛 2 | 🌐 Python | 📅 2021-06-03 - A plugin that generates tiny blurry placeholder images for lazy loading Wagtail images medium.com style.
* [Wagtail FilePreviews](https://github.com/filepreviews/wagtail-filepreviews) ⭐ 22 | 🐛 3 | 🌐 Python | 📅 2021-06-17 - Extend Wagtail's Documents with image previews and metadata from FilePreviews.io.
* [Wagtail CLIP](https://github.com/MattSegal/wagtail-clip) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2021-09-30 - A module for searching the contents of Wagtail images with natural language queries.
* [Wagtail Image Import](https://github.com/emilytoppm/wagtail-image-import) ⭐ 11 | 🐛 9 | 🌐 Python | 📅 2023-03-05 - A plugin for importing images from Google Drive.
* [Wagtail Stock Images](https://github.com/vicktornl/wagtail-stock-images) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2022-02-24 - Search stock images (e.g. via Unsplash) and save them to your Wagtail image library.
* [Wagtail Transcription](https://github.com/j-bodek/wagtail-transcription) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2025-12-31 - Provides a field to automatically creates transcriptions from YouTube videos.
* [Wagtail Makeup](https://github.com/torchbox/wagtail-makeup) ⭐ 6 | 🐛 2 | 🌐 Python | 📅 2025-10-29 - A plugin that replaces all your images with [Unsplash](https://unsplash.com/) images.

### Translations

* [Wagtail Localize](https://github.com/wagtail/wagtail-localize) ⭐ 246 | 🐛 149 | 🌐 Python | 📅 2026-01-25 - A translation plugin for the Wagtail CMS, allows pages or snippets to be translated within Wagtail's admin interface.
* [Wagtail Modeltranslation](https://github.com/infoportugal/wagtail-modeltranslation) ⭐ 155 | 🐛 28 | 🌐 Python | 📅 2026-02-03 - Simple app containing a mixin model that integrates [django-modeltranslation](https://github.com/deschler/django-modeltranslation) ⭐ 1,469 | 🐛 136 | 🌐 Python | 📅 2025-12-15 into Wagtail panels system.
* [wagtailtrans](https://github.com/wagtail/wagtailtrans) ⭐ 102 | 🐛 58 | 🌐 Python | 📅 2021-08-08 - A Wagtail add-on for supporting multilingual sites.

### Forms

* [Wagtail ReCaptcha](https://github.com/wagtail-nest/wagtail-django-recaptcha) ⭐ 62 | 🐛 18 | 🌐 Python | 📅 2025-02-20 - wagtail-django-captcha provides an easy way to integrate the [django-recaptcha](https://github.com/django-recaptcha/django-recaptcha) ⭐ 1,036 | 🐛 22 | 🌐 Python | 📅 2026-01-19 field when using the Wagtail formbuilder.
* [wagtail-contact-reply](https://github.com/KalobTaulien/wagtail-contact-reply) ⭐ 28 | 🐛 1 | 🌐 Python | 📅 2024-06-04 - Reply directly to form submissions from the Wagtail admin
* [Wagtail Model Forms](https://github.com/vicktornl/wagtail-model-forms) ⭐ 11 | 🐛 5 | 🌐 Python | 📅 2026-01-15 - The Wagtail Form Builder functionalities available for your models/snippets.
* [Wagtail Formation](https://github.com/mwesterhof/wagtail_formation) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2025-11-26 - Fully dynamic and easy to use CMS-able forms for wagtail
* [wagtailstreamforms](https://github.com/AccentDesign/wagtailstreamforms) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2022-02-18 - Build forms in Wagtail's admin for use in streamfields.
* [Wagtail JotForm](https://github.com/torchbox/wagtail-jotform) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2025-11-27 - Embeddable Jotform forms for Wagtail pages.
* [Wagtail Simple Captcha](https://github.com/acarasimon96/wagtail-django-simple-captcha) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2020-05-06 - A self-hosted alternative to Wagtail ReCaptcha that easily integrates a [django-simple-captcha](https://github.com/mbi/django-simple-captcha) ⭐ 1,428 | 🐛 39 | 🌐 Python | 📅 2025-12-07 field into the Wagtail form builder.
* [Wagtail's built in Form Builder](https://docs.wagtail.org/en/stable/reference/contrib/forms/) for general use cases.

### Testing

* [Wagtail Factories](https://github.com/wagtail/wagtail-factories) ⭐ 108 | 🐛 25 | 🌐 Python | 📅 2026-02-10 - Factory boy classes for Wagtail.
* [wagtail-linkchecker](https://github.com/neon-jungle/wagtail-linkchecker) ⭐ 52 | 🐛 1 | 🌐 Python | 📅 2024-06-24 - A tool to assist with finding broken links on your Wagtail site.
* [Wagtail Accessibility](https://github.com/wagtail-nest/wagtail-accessibility) ⭐ 34 | 🐛 5 | 🌐 Python | 📅 2024-11-20 – A plugin to assist with accessibility when developing in Wagtail.
* [Wagtail Foliage](https://github.com/harrislapiroff/wagtail-foliage) ⭐ 17 | 🐛 5 | 🌐 Python | 📅 2024-05-02 - Utilities for programmatically building page trees in Wagtail.

### Modeladmin

* [wagtail-treemodeladmin](https://github.com/cfpb/wagtail-treemodeladmin) ⭐ 53 | 🐛 4 | 🌐 Python | 📅 2025-12-01 - Page explorer-like navigation of Django model relationships using ModelAdmin.
* [wagtail-admin-list-controls](https://github.com/ixc/wagtail-admin-list-controls) ⭐ 51 | 🐛 9 | 🌐 Python | 📅 2025-09-05 - Adds advanced search, ordering and layout controls to Wagtail's modeladmin list views.
* [wagtail-rangefilter](https://github.com/wunderweiss/wagtail-rangefilter) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2026-01-12 - Integrates django-admin-rangefilter into Wagtail's ModelAdmin.

### Asynchronous (tasks)

* [Wagtail Celery Beat](https://github.com/Nigel2392/wagtail_celery_beat) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2024-02-22 - A way to manage your Django Celery Beat tasks inside of the Wagtail admin.

### Content Management

* [Wagtail Headless Preview](https://github.com/torchbox/wagtail-headless-preview) ⭐ 139 | 🐛 6 | 🌐 Python | 📅 2026-01-05 - Previews for headless Wagtail setups
* [Wagtail Themes](https://github.com/moorinl/wagtail-themes) ⭐ 108 | 🐛 2 | 🌐 Python | 📅 2024-09-02 - Site-specific theme loader for Wagtail.
* [Wagtail Transfer](https://github.com/wagtail/wagtail-transfer) ⭐ 102 | 🐛 42 | 🌐 Python | 📅 2026-02-07 - An official extension for Wagtail allowing content to be transferred between multiple instances of a Wagtail project
* [Wagtail Tag Manager](https://github.com/jberghoef/wagtail-tag-manager) ⭐ 78 | 🐛 17 | 🌐 Python | 📅 2024-02-28 - A Wagtail addon that allows for easier and GDPR compliant administration of scripts and tags.
* [Wagtail Sharing](https://github.com/cfpb/wagtail-sharing) ⭐ 56 | 🐛 5 | 🌐 Python | 📅 2025-11-10 – Easier sharing of Wagtail drafts.
* [Wagtail Content Import](https://github.com/torchbox/wagtail-content-import) ⭐ 37 | 🐛 6 | 🌐 Python | 📅 2026-02-09 - Import content from Google Docs or Docx into StreamFields, using a customisable mapping system.
* [Wagtail Import Export](https://github.com/torchbox/wagtail-import-export) ⚠️ Archived - Import/Export pages between Wagtail instances.
* [Wagtail Live Preview](https://github.com/KalobTaulien/wagtail-livepreview) ⚠️ Archived - Live page previews beside your content.
* [Wagtail-FEdit](https://github.com/Nigel2392/wagtail_fedit) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2025-06-04 - Add frontend editing to your Wagtail site.
* [Wagtail Import/Export Tool](https://github.com/berkalpyakici/wagtail-import-export-tool) ⭐ 12 | 🐛 3 | 🌐 Python | 📅 2019-07-03 - Refactor of [Wagtail Import Export](https://github.com/torchbox/wagtail-import-export) ⚠️ Archived. This tool supports importing/exporting images, documents, and snippets that are used on imported/exported pages.

### Misc

* [wagtailmenus](https://github.com/jazzband/wagtailmenus) ⭐ 419 | 🐛 21 | 🌐 Python | 📅 2025-11-29 - An extension for Torchbox's Wagtail CMS to help you manage and render multi-level navigation and simple flat menus in a consistent, flexible way.
* [Wagtail Grapple](https://github.com/torchbox/wagtail-grapple) ⭐ 158 | 🐛 63 | 🌐 Python | 📅 2026-01-05 - A Wagtail app that makes building GraphQL endpoints a breeze.
* [Wagtail Resume](https://github.com/adinhodovic/wagtail-resume) ⭐ 93 | 🐛 0 | 🌐 Python | 📅 2026-01-20 – A Wagtail project made to simplify creation of resumes for developers.
* [Wagtail Cache](https://github.com/coderedcorp/wagtail-cache) ⭐ 91 | 🐛 8 | 🌐 Python | 📅 2025-07-09 - A simple page cache for Wagtail using the Django cache middleware.
* [Wagtail Condensed Inline Panel](https://github.com/wagtail-deprecated/wagtail-condensedinlinepanel) ⚠️ Archived - Drop-in replacement for Wagtail's InlinePanel suited for large number of inlines (collapsible with drag and drop support).
* [Joyous](https://github.com/linuxsoftware/ls.joyous) ⭐ 77 | 🐛 12 | 🌐 Python | 📅 2024-02-05 - A calendar application for Wagtail.
* [Wagtail Gridder](https://github.com/wharton/wagtailgridder) ⭐ 67 | 🐛 1 | 🌐 Python | 📅 2025-07-29 - Grid card layout similar to Google image search results, with an expanded area for card details.
* [Wagtail Orderable](https://github.com/elton2048/wagtail-orderable) ⭐ 65 | 🐛 12 | 🌐 Python | 📅 2024-06-14 - Mixin support for drag-and-drop ordering in admin panel.
* [Wagtail Trash](https://github.com/Frojd/wagtail-trash) ⭐ 40 | 🐛 6 | 🌐 Python | 📅 2025-08-23 - Will place pages in a trash can from where they can be restored instead of being permanently deleted.
* [Wagtail GraphQL](https://github.com/tr11/wagtail-graphql) ⭐ 38 | 🐛 9 | 🌐 Python | 📅 2021-02-08 - App to automatically add GraphQL support to a Wagtail website.
* [Wagtail App Pages](https://github.com/mwesterhof/wagtail_app_pages) ⭐ 33 | 🐛 4 | 🌐 Python | 📅 2026-02-03 - Extend Wagtail pages using an actual URL config and django views.
* [Wagtail PDF View](https://github.com/donhauser/wagtail-pdf) ⭐ 29 | 🐛 0 | 🌐 Python | 📅 2025-01-30 - Render Wagtail pages and models as PDF document using Weasyprint or LaTeX.
* [Wagtail Secret Sharing](https://github.com/vicktornl/wagtail-secret-sharing) ⭐ 5 | 🐛 2 | 🌐 Python | 📅 2023-06-02 - Keep sensitive information out of your chat logs and email via a secure sharing protocol
* [Wagtail Cache Invalidator](https://github.com/vicktornl/wagtail-cache-invalidator) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2024-07-10 - Invalidate and purge (frontend) cache via an user-friendly interface in the Wagtail CMS.
* [Wagtail Word](https://github.com/Nigel2392/wagtail_word) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2024-02-22 - A way to upload your word (.docx, .doc) documents as pages to Wagtail.
* [Wagtail Error Pages](https://gitlab.com/alexgleason/wagtailerrorpages) - Pretty, smart, customizable error pages for Wagtail.

## Tools

### Templates & Starter Kits

* [CodeRed CMS](https://github.com/coderedcorp/coderedcms) ⭐ 756 | 🐛 60 | 🌐 Python | 📅 2025-12-16 - a professionally supported WordPress alternative for building marketing websites. Create pages, blogs, forms, and every Bootstrap 4 component in the wagtail admin out-of-the-box! [Learn more](https://www.coderedcorp.com/cms/) or [watch the lightning talk](https://www.youtube.com/watch?v=U1Y-jgeGh7g\&t=228s).
* [Wagtail Tailwind & Stimulus blog](https://github.com/AccordBox/wagtail-tailwind-blog) ⭐ 377 | 🐛 35 | 🌐 Python | 📅 2024-01-27 - A Wagtail blog based on Tailwind CSS, Stimulus, it supports Markdown, Latex and user comments.
* [Wagtail Pipit](https://github.com/Frojd/Wagtail-Pipit) ⭐ 251 | 🐛 62 | 🌐 Python | 📅 2026-02-08 – Pipit is a Wagtail boilerplate which aims to provide an easy and modern developer workflow with a React-rendered frontend.
* [Wagtail Cookiecutter Foundation](https://github.com/chrisdev/wagtail-cookiecutter-foundation) ⭐ 165 | 🐛 32 | 🌐 Python | 📅 2024-12-04 - A Cookiecutter template for Wagtail CMS using Zurb Foundation 6.
* [Django Cookiecutter Wagtail](https://github.com/Jean-Zombie/cookiecutter-django-wagtail) ⭐ 75 | 🐛 14 | 🌐 Python | 📅 2023-07-03 – A Django Cookiecutter template with Wagtail. Based on the original 'Django Cookiecutter'. Features: Docker support using `docker-compose` for development and production (using Traefik with LetsEncrypt support), customizable PostgreSQL version, Bootstrap 4, media storage using Amazon S3 or Google Cloud Storage and many more.
* [State Design System (DSFR) starter](https://github.com/numerique-gouv/sites-faciles) ⭐ 60 | 🐛 33 | 🌐 Python | 📅 2026-02-11 - Wagtail template and starter kit from the French government.
* [Wordpress to Wagtail migration kit](https://github.com/wagtail/wagtail-wordpress-import) ⭐ 56 | 🐛 37 | 🌐 Python | 📅 2026-01-26 - Import WordPress blog content from an XML file into Wagtail.
* [cookiecutter-wagtail-vix](https://github.com/engineervix/cookiecutter-wagtail-vix) ⭐ 40 | 🐛 14 | 🌐 Python | 📅 2026-02-02 - A matteries-included, reusable project skeleton to serve as a starting point for a Wagtail project.
* [Beginner Wagtail Cookiecutter](https://github.com/hminnovation/beginner-wagtail) ⭐ 30 | 🐛 2 | 🌐 Python | 📅 2017-01-23 – A super simple implementation of Wagtail CMS.
* [cookiecutter-wagtail-package](https://github.com/wagtail/cookiecutter-wagtail-package) ⭐ 21 | 🐛 4 | 🌐 Python | 📅 2024-07-08 - A cookiecutter template for building Wagtail add-on packages.
* [wagtail-webpack-dokku](https://github.com/helixsoftco/wagtail-webpack-dokku/) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2023-04-23 - A template with Wagtail, Webpack using django-webpack-loader, Bootstrap 5, production ready for Dokku.
* [Wagtail for Platform.sh](https://github.com/platformsh-templates/wagtail) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2025-12-08 - Wagtail template for Platform.sh.
* [Wagtail Quickstart with docker](https://github.com/saevarom/wagtail-start-docker) ⭐ 4 | 🐛 0 | 📅 2024-01-06 - A template repository to get started quickly with the latest Wagtail in docker.

### Templates (start command)

* [Wagtail news template](https://github.com/wagtail/news-template) ⭐ 152 | 🐛 26 | 🌐 Python | 📅 2025-04-26
* [Wagtail tutorial template](https://github.com/thibaudcolas/wagtail-tutorial-template) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-01-16

## Resources

### Getting started

* [Getting started in Wagtail, a newcomer's perspective](https://wagtail.org/blog/getting-started-wagtail-newcomers-perspective/) - Having used Drupal almost exclusively as my main tool of choice for a while now, I was asked to put together a build using Wagtail. By [@kiwimind](https://x.com/kiwimind).
* [Présentation de Wagtail, le dernier CMS Django](https://makina-corpus.com/django/presentation-de-wagtail-le-dernier-cms-django) - Wagtail est un CMS relativement récent dans l’écosystème Django. Pour autant, son jeune âge ne l’empêche pas de posséder de nombreuses fonctionnalités que nous découvrirons dans cet article.
* [Getting Started With Wagtail](https://vix.digital/insights/getting-started-wagtail/) - Working extensively with Wagtail and the surrounding community, we have discovered a range of common pitfalls developers run into when beginning to deliver with Wagtail.

### Articles

* [Extending The Functionality of Email Forms in Wagtail](https://lb.ee/posts/dev-wagtail-extending-the-functionality-of-email-forms-232c8469ac97/)
* [Wagtail: 2 Steps for Adding Pages Outside of the CMS](https://www.caktusgroup.com/blog/2016/02/15/wagtail-2-steps-adding-pages-outside-cms/)
* [Adding document previews to Wagtail CMS](https://filepreviews.io/blog/2017/04/20/adding-document-previews-to-wagtail/)
* [Wagtail Tutorials: Build Blog Step by Step](https://saashammer.com/blog/wagtail-tutorials/) - The tutorials teach you how to create a standard blog from scratch step by step.
* [Python CMS Framework Review: Wagtail vs Django-CMS](https://saashammer.com/blog/python-cms-framework-review-wagtail-vs-django-cms/) - Talk about the difference between Django-CMS and Wagtail, the two most popular CMS framework in Python world.
* [Deploying Wagtail In Production](https://vix.digital/insights/deploying-wagtail-production/)
* [Setting Up Foundation Sass With Wagtail](https://vix.digital/insights/setting-foundation-sass-wagtail/)
* [Upgrading to Wagtail 2.0](https://wagtail.org/blog/upgrading-to-wagtail-2/) – Wagtail 2.0 is one of our biggest releases to date.
* [Getting started with Draftail extensions](https://thib.me/getting-started-with-draftail-extensions) – Do you want to write extensions for Draftail? This is a good place to start.
* [Amplify a Wagtail/Django site](https://parbhatpuri.com/amplify-wagtail-django-site-urls-part-1.html) - Prepare you Wagtail site for Accelerated Mobile Pages (AMP).
* [Migrating your Drupal content to Wagtail](https://web.archive.org/web/20240929021314/https://medium.com/@kevinhowbrook/migrating-your-drupal-content-to-wagtail-d43bb34529e8) (archived)
* [How to Add Buttons to ModelAdmin Index View](https://timonweb.com/wagtail/how-to-add-buttons-to-modeladmin-index-view-in-wagtail-cms/)
* [How to Prevent Users from Creating Pages by Type](https://timonweb.com/wagtail/how-to-prevent-users-from-creating-certain-page-types-in-wagtail-cms/)
* [How to Create and Manage Menus of Wagtail application](https://saashammer.com/blog/how-to-create-and-manage-menus-in-wagtail/)
* [PythonEatsTail](https://pythoneatstail.com/en/) - Complete written and video tutorials to create a Wagtail site with multiple languages, authentication and more
* [Upgrading to Wagtail 3.0](https://enzedonline.com/en/tech-blog/upgrading-to-wagtail-3-0/) - General tips to migrate your codebase to Wagtail 3.0.
* [Upgrading to Wagtail 3.0 Part 1](https://cynthiakiser.com/blog/2022/06/01/wagtail-3-upgrade-part-1.html) & [Upgrading to Wagtail 3.0 Part 2](https://cynthiakiser.com/blog/2022/06/02/wagtail-3-upgrade-part-2.html) - Two part series in how to migrate to Wagtail 3.0 with specific code examples.
* [Multi-tenancy with Wagtail](https://cynthiakiser.com/blog/2023/11/01/multitenancy-with-wagtail.html) - Multiple part guide on robust multi-tenancy support in Wagtail.

### Recipes

* [Consumer Financial Protection Bureau Wagtail development guide](https://github.com/cfpb/development/blob/main/guides/unittesting-django-wagtail.md) ⭐ 67 | 🐛 32 | 🌐 Shell | 📅 2023-07-07 - Unit Testing Django and Wagtail
* [Serafeim's Wagtail FAQ](https://github.com/spapas/wagtail-faq) ⭐ 43 | 🐛 0 | 📅 2023-02-12 - Answers and recipes for Wagtail
* [Oscar Wagtail demo project](https://github.com/LUKKIEN/oscar-wagtail-demo) ⚠️ Archived - A Django recipe for integrating Oscar E-commerce into a Wagtail CMS application.

### Presentations

* [wagtail-textract – Wagtail Space 2019](https://www.youtube.com/watch?t=3313\&v=CSwpj-jyjP4) by Kees Hink. [Code](https://github.com/fourdigits/wagtail_textract) ⭐ 34 | 🐛 14 | 🌐 Python | 📅 2023-10-25.
* [SEO dashboard – Wagtail Space 2019](https://www.youtube.com/watch?t=3937\&v=CSwpj-jyjP4) by Janneke Janssen. [Code](https://github.com/LUKKIEN/wagtail-marketing-addons) ⭐ 22 | 🐛 5 | 🌐 Python | 📅 2025-04-28.
* [Wagtail Space easter egg team demo – Wagtail Space 2018](https://www.youtube.com/watch?v=u0CPaXRSOzI\&t=2057s) by Lars. [Code](https://github.com/specialunderwear/haunted-wagtail) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2018-03-16.
* [An Introduction to Wagtail](https://www.youtube.com/watch?v=glIIF-kBXf0) by Eloise "Ducky" Macdonald-Meyer - This talk is an introduction to Wagtail, a content management system built on the Python web framework, Django.
* [DjangoCon US 2015 - Wagtail - Yet Another Django CMS](https://www.youtube.com/watch?v=6j0NVq6g4FE) by Tom Dyson - Tom will explain why his agency decided to build a new CMS, share some lessons learned in running a growing open source project, and outline Wagtail's roadmap to version 2 and beyond. [Slide deck](https://speakerdeck.com/tomdyson/wagtail-yet-another-cms-djangocon-us-2015).
* [Wellington Wagtail CMS Meetup - Meet Wagtail](https://docs.google.com/presentation/d/19EGWFtfHovHSAvyHCnLbxK50IAR2o7WwKd709cqi9p4/edit) by Josh, Jordi and Rich, from the Springload dev team - An introductory session to Wagtail to showcase the main features it has to offer.
* [DjangoCon US 2016 - Atomic Wagtail](https://www.youtube.com/watch?v=kqAKiouk1lY) by Kurt Wall – Brad Frost's atomic design principles are taking the way we design the web by storm. I'll explain what Wagtail is, how you can use it with atomic design principles, and some hurdles you might run into along the way with suggestions on how to help.
* [PyCon Australia – Comparing Wagtail, Django CMS and Mezzanine](https://www.youtube.com/watch?v=3UC1MNFOjEI) by Adam Brenecki – This talk explores the different approaches, strengths and weaknesses of each CMS, and what they mean for you as a developer and for your content editors.
* [Wagtail — еще одна CMS на Django](https://www.youtube.com/watch?v=yRmZ6WUfoOc) by Mikalai Radchuk - This talk is an introduction to Wagtail in Russian.
* [Wagtail & Agile – Wagtail Space 2017](https://www.youtube.com/watch?t=2m21s\&v=-Qii_AyQsxE) by Edd Baldry.
* [Deploy Wagtail to the Divio Cloud – Wagtail Space 2017](https://www.youtube.com/watch?t=38m13s\&v=-Qii_AyQsxE) by Daniele Procida.
* [All about Wagtail – Wagtail Space 2017](https://www.youtube.com/watch?v=OedQi5W3Zho) by Robin van der Rijst.
* [Presenting Wagtail Clear StreamField, a modular StreamField app – Wagtail Space 2017](https://www.youtube.com/watch?t=19m1s\&v=OedQi5W3Zho) by Edd Baldry.
* [Wagtail Experiments, easy A/B testing for your Wagtail sites – Wagtail Space 2017](https://www.youtube.com/watch?t=34m37s\&v=OedQi5W3Zho) by Tom Dyson.
* [Wagtail's preview, a new hope – Wagtail Space 2017](https://www.youtube.com/watch?v=ObM2pUgY-bs) by Bertrand Bordage.
* [The Zen of Wagtail – Wagtail Space 2017](https://www.youtube.com/watch?t=16m38s\&v=ObM2pUgY-bs) by Matt Westcott.
* [Plone to Wagtail – Wagtail Space 2017](https://www.youtube.com/watch?t=2m57s\&v=hZcuq8WJVew) by Coen van der Kamp.
* [Hundreds of Wagtail in Flight – Wagtail Space 2017](https://www.youtube.com/watch?t=24m9s\&v=hZcuq8WJVew) by Simon de Haan.
* [How Google uses Wagtail – Wagtail Space 2018](https://www.youtube.com/watch?v=lh9nmN1mzwQ\&t=1937s) by Kevin Chung.
* [Introducing Draft.js in Wagtail – Wagtail Space 2018](https://www.youtube.com/watch?v=lh9nmN1mzwQ\&t=2690s) by Thibaud Colas. [Presentation](https://thib.me/introducing-draft-js-in-wagtail).
* [Let It Go – Wagtail Space 2018](https://www.youtube.com/watch?v=lh9nmN1mzwQ\&t=3938s) by Matt Wescott.
* [Developing Solutions for Girls, by Men – Wagtail Space 2018](https://www.youtube.com/watch?v=lh9nmN1mzwQ\&t=5184s) by Lisa Adams.
* [Wagtail’s first hatch – Wagtail Space 2018](https://www.youtube.com/watch?v=P8RUQE7Djdg\&t=265s) by Bertrand Bordage.
* [The Word Problem – Wagtail Space 2018](https://www.youtube.com/watch?v=P8RUQE7Djdg\&t=2841s) by Tom Dyson.
* [Wagtail on Divio Cloud – Wagtail Space 2018](https://www.youtube.com/watch?v=P8RUQE7Djdg\&t=3856s) by Daniele Procida.
* [Chopping the head off Wagtail and sticking it back on – Wagtail Space 2018](https://www.youtube.com/watch?v=u0CPaXRSOzI\&t=152s) by Tony Yates.
* [StreamField editor at UWKM – Wagtail Space 2018](https://www.youtube.com/watch?v=u0CPaXRSOzI\&t=400s) by Geert jan Hoogeslag.
* [Things i learned at Wagtail Space – Wagtail Space 2018](https://www.youtube.com/watch?v=u0CPaXRSOzI\&t=719s) by Codie Roelf.
* [Fly Wagtail to a PyCon – Wagtail Space 2018](https://www.youtube.com/watch?v=u0CPaXRSOzI\&t=912s) by Daniele Procida.
* [Wagtail Performance – Wagtail Space 2018](https://www.youtube.com/watch?v=u0CPaXRSOzI\&t=1345s) by Michael van Tellingen. [Code](https://gist.github.com/mvantellingen/daebda6abbaa9a5ed0888f886a77fcf0).
* [Mutliple images uploader – Wagtail Space 2018](https://www.youtube.com/watch?v=u0CPaXRSOzI\&t=1661s) by Rajeev J Sebastian.
* [Wagtail Space 2019 – Wagtail Space 2018](https://www.youtube.com/watch?v=u0CPaXRSOzI\&t=2278s) by Maarten Kling.
* [Wagtail in 2018 – Wagtail Space US 2018](https://www.youtube.com/watch?v=ICKYMO0YoFI\&index=2\&list=PLEyaio0l1qoGGbXg3XH0205FIF32oO1wV) by Tom Dyson.
* [What the Wagtail Docs Don't Tell You – Wagtail Space US 2018](https://www.youtube.com/watch?v=PCkxBNXWM64\&index=3\&list=PLEyaio0l1qoGGbXg3XH0205FIF32oO1wV) by Lacey Williams Henschel.
* [Django Logging for Wagtail – Wagtail Space US 2018](https://www.youtube.com/watch?v=kkztl9ORUKQ\&list=PLEyaio0l1qoGGbXg3XH0205FIF32oO1wV\&index=4) by Ryan Sullivan.
* [Scaling Wagtail for 100 Million Girls – Wagtail Space US 2018](https://www.youtube.com/watch?v=AiOJAKE0M0I\&index=5\&list=PLEyaio0l1qoGGbXg3XH0205FIF32oO1wV) by Lisa Adams and Codie Roelf.
* [Using Wagtail to Fight for Press Freedom – Wagtail Space US 2018](https://www.youtube.com/watch?v=FYqbqsa04T8\&list=PLEyaio0l1qoGGbXg3XH0205FIF32oO1wV\&index=6) by Harris Lapiroff.
* [Choosing Wagtail for Columbia University – Wagtail Space US 2018](https://www.youtube.com/watch?v=OiZScRcluCo\&list=PLEyaio0l1qoGGbXg3XH0205FIF32oO1wV\&index=7) by Zarina Mustapha.
* [Running a Multi-Site Newsroom in Wagtail – Wagtail Space US 2018](https://www.youtube.com/watch?v=lMCjInjAz-M\&list=PLEyaio0l1qoGGbXg3XH0205FIF32oO1wV\&index=8) by Ryan Verner.
* [Wagtail in the Cloud – Wagtail Space US 2018](https://www.youtube.com/watch?v=N1MeTEPRmJA\&index=9\&list=PLEyaio0l1qoGGbXg3XH0205FIF32oO1wV) by Daniele Procida.
* [Beheading Wagtail: Wagtail as a Headless CMS – Wagtail Space US 2018](https://www.youtube.com/watch?v=HZT14u6WwdY\&index=10\&list=PLEyaio0l1qoGGbXg3XH0205FIF32oO1wV) by Michael Harrison.
* [Learning Wagtail – Wagtail Space US 2018](https://www.youtube.com/watch?v=C-tXt5fLj_s\&index=11\&list=PLEyaio0l1qoGGbXg3XH0205FIF32oO1wV) by Dawn Wages.
* [Sharing is Caring – Wagtail Space US 2018](https://www.youtube.com/watch?v=6AXyg6vvMTE\&index=12\&list=PLEyaio0l1qoGGbXg3XH0205FIF32oO1wV) by Andy Chosak.
* [Lightning Talks – Wagtail Space US 2018](https://www.youtube.com/watch?v=uoxyBIpaXTU\&index=13\&list=PLEyaio0l1qoGGbXg3XH0205FIF32oO1wV)
* [Wagtail: когда хочется чего-то приятнее, чем просто Django – Moscow Python Conf++ 2018](https://www.youtube.com/watch?v=xPPfTvLS7oQ) by Игорь Мосягин
* [The State of Wagtail – Wagtail Space 2019](https://www.youtube.com/watch?t=592\&v=MAzZ2lhMhzM) by Tom Dyson.
* [Image rotation feature – Wagtail Space 2019](https://www.youtube.com/watch?t=2057\&v=MAzZ2lhMhzM) by Chris Adams. Code.
* [Debug templates – Wagtail Space 2019](https://www.youtube.com/watch?t=2264\&v=MAzZ2lhMhzM) by Coen van der Kamp.
* [Wagtail Headless with HATEOAS – Wagtail Space 2019](https://www.youtube.com/watch?t=2567\&v=MAzZ2lhMhzM) by Duco Dokter.
* [Building a Planet Friendly Web (with Wagtail) – Wagtail Space 2019](https://www.youtube.com/watch?t=2926\&v=MAzZ2lhMhzM) by Chris Adams.
* [\[WIP\] The future of (rich text) authoring experiences in Wagtail – Wagtail Space 2019](https://www.youtube.com/watch?t=4067\&v=MAzZ2lhMhzM) by Thibaud Colas.
* [Wagtail & Whatsapp – Wagtail Space 2019](https://www.youtube.com/watch?t=47\&v=CSwpj-jyjP4) by Lisa Adams & Codie Roelf.
* [Slack2Wagtail – Wagtail Space 2019](https://www.youtube.com/watch?t=785\&v=CSwpj-jyjP4) by Coen van der Kamp & Lucas Moeskops.
* [Wagtail and Oscar – Wagtail Space 2019](https://www.youtube.com/watch?t=1634\&v=CSwpj-jyjP4) by Lars van de Kerkhof.
* [Django 2.2 compatibility – Wagtail Space 2019](https://www.youtube.com/watch?t=3468\&v=CSwpj-jyjP4) by Matt Wescott.
* [My First Wagtail Contribution – More formats in RichText Editor – Wagtail Space 2019](https://www.youtube.com/watch?t=4126\&v=CSwpj-jyjP4) by Arifin Ibne Matin.
* [Fly, Wagtail, fly! – Wagtail Space 2019](https://www.youtube.com/watch?t=4404\&v=CSwpj-jyjP4) by Daniele Procida.
* [Wagtail & GraphQL – Wagtail Space 2019](https://www.youtube.com/watch?t=24\&v=YydSbL8gMS4) by Arthur Bayr.
* [Writing (code) for authors – Wagtail Space US 2019](https://www.youtube.com/watch?v=Ihsrki0d1G8\&list=PLEyaio0l1qoEIUFM9bnRKoN6VKEUOdxAn\&index=1) by Brian Smith & Eric Sherman. [Slides](https://docs.google.com/presentation/d/1z61u0uKwJxmYS4Zawbu4Zgg-kCtInd1VgsEg-rnwzBE/edit).
* [Saving Lives With Wagtail: Recovery Meetings Across the World – Wagtail Space US 2019](https://www.youtube.com/watch?v=QlLWvNT5Wrk\&list=PLEyaio0l1qoEIUFM9bnRKoN6VKEUOdxAn\&index=2) by Timothy Allen.
* [Why we chose Wagtail for CodeRed CMS – Wagtail Space US 2019](https://www.youtube.com/watch?v=1JUOAAmLQFA\&list=PLEyaio0l1qoEIUFM9bnRKoN6VKEUOdxAn\&index=3) by Vince Salvino.
* [Building a Wagtail-based site and authoring environment with accessibility in mind – Wagtail Space US 2019](https://www.youtube.com/watch?v=CxjlAI6R7iY\&list=PLEyaio0l1qoEIUFM9bnRKoN6VKEUOdxAn\&index=4) by Zarina Mustapha.
* [Making Wagtail Accessible – Wagtail Space US 2019](https://www.youtube.com/watch?v=tdB1I_gSCeY\&list=PLEyaio0l1qoEIUFM9bnRKoN6VKEUOdxAn\&index=5) by Thibaud Colas. [Slides](https://docs.google.com/presentation/d/15y8XIe7SL-RYEO9tEE8n9chx80_X4j4PbczGGM-cEGE/edit).
* [Everyone can fly a flag – Wagtail Space US 2019](https://www.youtube.com/watch?v=ZqwmgsqMTEs\&list=PLEyaio0l1qoEIUFM9bnRKoN6VKEUOdxAn\&index=6) by Will Barton. [Slides](https://docs.google.com/presentation/d/1-A1doke2ylcqG72oIP-MLiX8SKXKkKNxQeKxddYUGBw/edit).
* [Architecting for a multi-domain site – Wagtail Space US 2019](https://www.youtube.com/watch?v=xMbJmHF7kCw\&list=PLEyaio0l1qoEIUFM9bnRKoN6VKEUOdxAn\&index=7) by Ben Beecher. [Slides](https://slides.com/benbeecher/mds/).
* [Contributions can be more than code – Wagtail Space US 2019](https://www.youtube.com/watch?v=tK-3kEBbblg\&list=PLEyaio0l1qoEIUFM9bnRKoN6VKEUOdxAn\&index=8) by Kalob Taulien.
* [Thoughtful Code Review – Wagtail Space US 2019](https://www.youtube.com/watch?v=RY0K1BEV-_U\&list=PLEyaio0l1qoEIUFM9bnRKoN6VKEUOdxAn\&index=9) by Naomi Morduch Toubman. [Slides](https://docs.google.com/presentation/d/1b_Hda8381G6mMc7uzYDc2EYjocfwSi2TYiRMI7d4e3I/edit).
* [Solving your problems by spelunking the Wagtail code – Wagtail Space US 2019](https://www.youtube.com/watch?v=BMoOhjgirFM\&list=PLEyaio0l1qoEIUFM9bnRKoN6VKEUOdxAn\&index=10) by Harris Lapiroff. [Slides](https://harrislapiroff.github.io/wagtail-space-us-2019/)
* [The State of Wagtail: 2019 – Wagtail Space US 2019](https://www.youtube.com/watch?v=s29vaGnFcq8\&list=PLEyaio0l1qoEIUFM9bnRKoN6VKEUOdxAn\&index=11) by Tom Dyson.
* [Wagtail Guide - Getting started - Wagtail Space US 2022](https://www.youtube.com/watch?v=E3-kFY6jPPY) by Coen van der Kamp.
* [A New Approach to Multitenant Wagtail - Wagtail Space US 2022](https://www.youtube.com/watch?v=WN0L4YNrWes) by Stephanie C. Smith and Addison Hardy.
* [The Wagtail Marketplace for Games-based Courses - Wagtail Space 2022](https://www.youtube.com/watch?v=ueou6CxiR3Y) by Sarah Toms.
* [The Wagtail Ecosystem - Wagtail Space US 2022](https://www.youtube.com/watch?v=4Qd43nsxmoc) by Vince Salvino.
* [Wagtail charts and graphs - Wagtail Space US 2022](https://www.youtube.com/watch?v=QK-Vhlpos3Q) by Sævar Öfjörð Magnússon & Arnar Tumi Þorsteinsson.
* [Wagtail as a headless CMS for JavaScript frontends - Wagtail Space US 2022](https://www.youtube.com/watch?v=bYRQ492BED0) by Tommaso Amici.
* [Adding a GraphQL API to Wagtail - Wagtail Space US 2022](https://www.youtube.com/watch?v=_O5isU354vg) by Patrick Arminio.
* [Bringing JSONField into Wagtail Core - Wagtail Space US 2022](https://www.youtube.com/watch?v=XtazMDNdlK8) by Sage Abdullah.
* [Wagtail vs. WordPress - Wagtail Space US 2022](https://www.youtube.com/watch?v=Vl2g7H3aodw) by Kalob Taulien.
* [Designing the new page editor - Wagtail Space US 2022](https://www.youtube.com/watch?v=t2xiPJ91UCE) by Phil Dexter and Ben Enright.
* [5 Things I Learned About Wagtail the Hard Way - Wagtail Space US 2022](https://www.youtube.com/watch?v=LNqVzLkZkig) by Meagen Voss.
* [Tips for Maintaining Wagtail Packages - Wagtail Space US 2022](https://www.youtube.com/watch?v=Zh608nVBrEw) by Tim Allen.
* [Wagtail Guide - Wagtail Space US 2022](https://www.youtube.com/watch?v=W0tL-5V5BWA) by Coen van der Kamp.
* [The state of Wagtail 2022 - Wagtail Space NL 2022](https://www.youtube.com/watch?v=4D49RENHfoM) by Tom Dyson.
* [Choosers - Wagtail Space NL 2022](https://www.youtube.com/watch?v=nSjVAISLr4M) by Matthew Westcott.
* [Working with Image Filters - Wagtail Space NL 2022](https://www.youtube.com/watch?v=gCGT51BcTdM) by Arnar Tumi Þorsteinsson.
* [Things I learned - Wagtail Space NL 2022](https://www.youtube.com/watch?v=xG5-s48TZt8) by Dan Braghis.
* [Wagtail Roadrunner Beep Beep - Wagtail Space NL 2022](https://www.youtube.com/watch?v=ynlFUcutSWQ) by Lars van de Kerkhof.
* [Dockerising wagtail projects in 5 minutes - Wagtail Space NL 2022](https://www.youtube.com/watch?v=PgkpBMoN4UY) by Sævar Öfjörð Magnússon.
* [Wagtail in the News Room - Wagtail Space NL 2022](https://www.youtube.com/watch?v=B85HwmX5uaw) by Sævar Öfjörð Magnússon & Arnar Tumi Þorsteinsson.
* [Digital Nomad - Wagtail Space NL 2022](https://www.youtube.com/watch?v=9Evrwzpg-dw) by Maikel Martens.
* [Unobtrusive internationalisation - Wagtail Space NL 2022](https://www.youtube.com/watch?v=_dhScxTdtjA) by Lars van de Kerkhof.
* [Moving Wagtail pages - Wagtail Space NL 2022](https://www.youtube.com/watch?v=OFqPKffSVWI) by Viggo de Vries.
* [Wagtail architecture options, or should I go headless - Wagtail Space NL 2022](https://www.youtube.com/watch?v=JMULuz6RzjQ) by Dan Braghis.
* [Wagtail headless and NextJS frontend - Wagtail Space NL 2022](https://www.youtube.com/watch?v=s8cJhFtjqZA) by Lucas Moeskops.
* [State of Wagtail - Wagtail Space US 2024](https://www.youtube.com/watch?v=TKLYeKpFbno\&list=PLfwZ-fob20cMduvPwjstgycu-Z_1QwJQB) by Tom Dyson.
* [Pleasant Publishing Patterns - Wagtail Space US 2024](https://www.youtube.com/watch?v=ZXGcqY-OeYk\&list=PLfwZ-fob20cMduvPwjstgycu-Z_1QwJQB) by Michael Trythall.
* [Accessibility for Complex Components and Interfaces - Wagtail Space US 2024](https://www.youtube.com/watch?v=AC1gy9R2Z6c\&list=PLfwZ-fob20cMduvPwjstgycu-Z_1QwJQ) by Kara Gaulrapp.
* [One Thousand and One Wagtail Sites - Wagtail Space US 2024](https://www.youtube.com/watch?v=yciVqzSGWTw\&list=PLfwZ-fob20cMduvPwjstgycu-Z_1QwJQB) by Vince Salvino.
* [3D Files with Wagtail - Wagtail Space US 2024](https://www.youtube.com/watch?v=ccBrb50xRCM\&list=PLfwZ-fob20cMduvPwjstgycu-Z_1QwJQ) by Dawn Wages and Mira Gibson.
* [Wagtail, Reactivated - Headless Without the Headache - Wagtail Space US 2024](https://www.youtube.com/watch?v=mQsI8Ji3_LY\&list=PLfwZ-fob20cMduvPwjstgycu-Z_1QwJQB) by Josh Marantz.
* [Lightning Talks June 20 - Wagtail Space US 2024](https://www.youtube.com/watch?v=UuE3Y15To8Q\&list=PLfwZ-fob20cMduvPwjstgycu-Z_1QwJQ) - lightning talks.
* [LLMs and Wagtail - Wagtail Space US 2024](https://www.youtube.com/watch?v=b-luIDn80bc\&list=PLfwZ-fob20cMduvPwjstgycu-Z_1QwJQB) by Emily Topp-Mugglestone.
* [PudlStack - Building Wagtail Affinity Group Communities That Offer Bot Helpers - Wagtail Space US 2024](https://www.youtube.com/watch?v=SNEeo_ABQ7g\&list=PLfwZ-fob20cMduvPwjstgycu-Z_1QwJQB) by Anthony Garcia.
* [Auditing Wagtail Content - Wagtail Space US 2024](https://www.youtube.com/watch?v=a1O3hKib8Ns\&list=PLfwZ-fob20cMduvPwjstgycu-Z_1QwJQB\&index=2\&pp=i) by Will Barton & Chuck Sebian-Lander.
* [What Editors Really Want - Wagtail Space US 2024](https://www.youtube.com/watch?v=1qF5wC4rCY4\&list=PLfwZ-fob20cMduvPwjstgycu-Z_1QwJQ) by Meagen Voss.
* [Improving the Editor Experience through Validation - Wagtail Space US 2024](https://www.youtube.com/watch?v=UVBHciwpgKM\&list=PLfwZ-fob20cMduvPwjstgycu-Z_1QwJQ) by Scott Cranfill.
* [sditail: Extending Wagtail CMS as a Spatial Data Infrastructure - Wagtail Space US 2024](https://www.youtube.com/watch?v=XxdJpYNT4EM\&list=PLfwZ-fob20cMduvPwjstgycu-Z_1QwJQ) by César Benjamin.
* [Packages! Packages! Packages! - Wagtail Space US 2024](https://www.youtube.com/watch?v=r5ovJPWvxL4\&list=PLfwZ-fob20cMduvPwjstgycu-Z_1QwJQ) - panel.
* [Lightning Talks June 21 - Wagtail Space US 2024](https://www.youtube.com/watch?v=vazMp9jTlEU\&list=PLfwZ-fob20cMduvPwjstgycu-Z_1QwJQ) - lightning talks.
* [The State of Wagtail - Wagtail Space NL 2024](https://www.youtube.com/watch?v=P9Ftbu5NVUI\&list=PLEyaio0l1qoGj7XTEuNXT2o3tYpuSmlbP\&index=1) by Tom Dyson.
* [Headless Wagtail Strategies - Wagtail Space NL 2024](https://www.youtube.com/watch?v=nweVHX5DgWU\&list=PLEyaio0l1qoGj7XTEuNXT2o3tYpuSmlbP\&index=2) by Rémy Sanchez.
* [Wagging HubSpot's Tail - Wagtail Space NL 2024](https://www.youtube.com/watch?v=VUoOoRxlWrU\&list=PLEyaio0l1qoGj7XTEuNXT2o3tYpuSmlbP\&index=3) by Simon Blanchard and Joost Meijerink.
* [Wagtail and Caching - Wagtail Space NL 2024](https://www.youtube.com/watch?v=vBdG2GfAZAo\&list=PLEyaio0l1qoGj7XTEuNXT2o3tYpuSmlbP\&index=4) by Jake Howard.
* [Faster Thumbnails for a Faster Web - Wagtail Space NL 2024](https://www.youtube.com/watch?v=0kHhGBxwzeM\&list=PLEyaio0l1qoGj7XTEuNXT2o3tYpuSmlbP\&index=5) by Alex Tomkins.
* [The impossible art of making everyone happy - Wagtail Space NL 2024](https://www.youtube.com/watch?v=v3KEaMTfKg0\&list=PLEyaio0l1qoGj7XTEuNXT2o3tYpuSmlbP\&index=6) by Matthew Westcott.
* [Bringing modern authentication to Wagtail: WebAuthn and Passkeys - Wagtail Space NL 2024](https://www.youtube.com/watch?v=qJwg2kFtFW4\&list=PLEyaio0l1qoGj7XTEuNXT2o3tYpuSmlbP\&index=7) by Storm Heg.
* [How to abuse Wagtail's StreamFields as much as you want - Wagtail Space NL 2024](https://www.youtube.com/watch?v=tOBGJ0riDRw\&list=PLEyaio0l1qoGj7XTEuNXT2o3tYpuSmlbP\&index=8) by Rémy Sanchez.
* [Wagtail AI and Wagtail Vector Index - Wagtail Space NL 2024](https://www.youtube.com/watch?v=jHuhX_SNF1s\&list=PLEyaio0l1qoGj7XTEuNXT2o3tYpuSmlbP\&index=9) by Dan Braghiș.
* [Wagtail Translate - Wagtail Space NL 2024](https://www.youtube.com/watch?v=QxnC70Bwj0k\&list=PLEyaio0l1qoGj7XTEuNXT2o3tYpuSmlbP\&index=10) by Coen van der Kamp.
* [You've been caching your content website wrong - Wagtail Space NL 2024](https://www.youtube.com/watch?v=bWF06aCjbUM\&list=PLEyaio0l1qoGj7XTEuNXT2o3tYpuSmlbP\&index=11) by Rémy Sanchez.
* [Universal Listings - Wagtail Space NL 2024](https://www.youtube.com/watch?v=aNto27_lfJ4\&list=PLEyaio0l1qoGj7XTEuNXT2o3tYpuSmlbP\&index=12) by Sage Abdullah.
* [Recovering deleted Django models - Wagtail Space NL 2024](https://www.youtube.com/watch?v=TB64DtQZeB0\&list=PLEyaio0l1qoGj7XTEuNXT2o3tYpuSmlbP\&index=13) by Jake Howard.
* [Wagtail Dashboards - Wagtail Space NL 2024](https://www.youtube.com/watch?v=0msxKe0RoNw\&list=PLEyaio0l1qoGj7XTEuNXT2o3tYpuSmlbP\&index=14) by Judith van Leersum and Emmelien Schiet.
* [Multi-lingual websites in Wagtail - Wagtail Space NL 2024](https://www.youtube.com/watch?v=5rPvOsVeRhA\&list=PLEyaio0l1qoGj7XTEuNXT2o3tYpuSmlbP\&index=15) by Paul Stevens.
* [State of Wagtail 2025 - Wagtail Space 2025](https://www.youtube.com/watch?v=9Kduqs6NH7Q\&list=PLfwZ-fob20cPI9_fnG_ULYIdOS5TKP1IZ\&index=2) by Thibaud Colas.
* [Wagtail in industry: from farming to finance - Wagtail Space 2025](https://www.youtube.com/watch?v=DH87OzXzj28\&list=PLfwZ-fob20cPI9_fnG_ULYIdOS5TKP1IZ\&index=3) by Vince Salvino.
* [Redesigning and refactoring Wagtail components - Wagtail Space 2025](https://www.youtube.com/watch?v=8h0fxe7b8s8\&list=PLfwZ-fob20cPI9_fnG_ULYIdOS5TKP1IZ\&index=4) by Mariana.
* [Building Better Wagtail Sites: Traits of a Good CMS - Wagtail Space 2025](https://www.youtube.com/watch?v=n5KHTLS22YE\&list=PLfwZ-fob20cPI9_fnG_ULYIdOS5TKP1IZ\&index=5) by Michael Trythall.
* [REX: Building a SaaS from Wagtail - Wagtail Space 2025](https://www.youtube.com/watch?v=3T-ITKTByH4\&list=PLfwZ-fob20cPI9_fnG_ULYIdOS5TKP1IZ\&index=6) by Sébastien Corbin.
* [Implement the French Government Design System in Wagtail - Wagtail Space 2025](https://www.youtube.com/watch?v=8_CBltGuv0g\&list=PLfwZ-fob20cPI9_fnG_ULYIdOS5TKP1IZ\&index=7) by Sylvain Boissel and Lucie Laporte.
* [Wagtail Nest: Maintaining Community Packages Together - Wagtail Space 2025](https://www.youtube.com/watch?v=h0kKy4R5kNY\&list=PLfwZ-fob20cPI9_fnG_ULYIdOS5TKP1IZ\&index=8) by Coen van der Kamp.
* [Automated Data Loader: Wagtail for Weather Data Integration - Wagtail Space 2025](https://www.youtube.com/watch?v=iTxcq__Gcr4\&list=PLfwZ-fob20cPI9_fnG_ULYIdOS5TKP1IZ\&index=9) by Erick Otenyo and Grace Amondi.
* [Building Flexible Wagtail CMS Experiences for Editors - Wagtail Space 2025](https://www.youtube.com/watch?v=-azqKJdEivk\&list=PLfwZ-fob20cPI9_fnG_ULYIdOS5TKP1IZ\&index=10) by Annette Lewis and Eric Sherman.
* [Building a little YouTube on Wagtail - Wagtail Space 2025](https://www.youtube.com/watch?v=hLw3FWb2LfQ\&list=PLfwZ-fob20cPI9_fnG_ULYIdOS5TKP1IZ\&index=11) by Tom Dyson.
* [Creating connections between stories and objects using AI - Wagtail Space 2025](https://www.youtube.com/watch?v=Wkjm8xdV_6c\&list=PLfwZ-fob20cPI9_fnG_ULYIdOS5TKP1IZ\&index=12) by Trish Thomas.
* [AI in Wagtail: responsible innovation for content editors - Wagtail Space 2025](https://www.youtube.com/watch?v=n2fIFJLSH5E\&list=PLfwZ-fob20cPI9_fnG_ULYIdOS5TKP1IZ\&index=16) by Sage Abdullah and Tom Usher.
* [The Bogotá Digital Library: A Wagtail Success Story - Wagtail Space 2025](https://www.youtube.com/watch?v=cbANVWkDIs0\&list=PLfwZ-fob20cPI9_fnG_ULYIdOS5TKP1IZ\&index=17) by Juan Aguayo.
* [Wagtail and AI Agentic Coding - Wagtail Space 2025](https://www.youtube.com/watch?v=pukU8F3ciEM\&list=PLfwZ-fob20cPI9_fnG_ULYIdOS5TKP1IZ\&index=18) by Maciej Baron.
* [The Impact of A Contribution to Wagtail - Wagtail Space 2025](https://www.youtube.com/watch?v=sW8k4F1DY18\&list=PLfwZ-fob20cPI9_fnG_ULYIdOS5TKP1IZ\&index=19) by Chiemezuo Akujobi.
* [One URL to Rule Them All: Dynamic Landing Pages in Wagtail - Wagtail Space 2025](https://www.youtube.com/watch?v=UOEvu4Lyj8w\&list=PLfwZ-fob20cPI9_fnG_ULYIdOS5TKP1IZ\&index=20) by Chrissy Wainwright and Doug Harris.
* [Fact checking with Wagtail - Wagtail Space 2025](https://www.youtube.com/watch?v=Spdt-W5XotM\&list=PLfwZ-fob20cPI9_fnG_ULYIdOS5TKP1IZ\&index=21) by Jon Chittenden and Craig Dawson.
* [Sympa newsletters with Wagtail - Wagtail Space 2025](https://www.youtube.com/watch?v=n7bM54MAc24\&list=PLfwZ-fob20cPI9_fnG_ULYIdOS5TKP1IZ\&index=22) by Agnès Haasser.
* [Code that creates content - Wagtail Space 2025](https://www.youtube.com/watch?v=XkSX195ssjY\&list=PLfwZ-fob20cPI9_fnG_ULYIdOS5TKP1IZ\&index=23) by Alex Morega.
* [Who's that code snippet? A screen reader guessing game - Wagtail Space 2025](https://www.youtube.com/watch?v=VkPOe_JixTI\&list=PLfwZ-fob20cPI9_fnG_ULYIdOS5TKP1IZ\&index=24) by Laura Wissiak and Pawel Masarczyk.
* [Bird Meets Bot: Using AI Tools to Make Wagtail Smarter - Wagtail Space 2025](https://www.youtube.com/watch?v=SsjXnpuLnL0\&list=PLfwZ-fob20cPI9_fnG_ULYIdOS5TKP1IZ\&index=25) by Alex Tomkins.
* [Where next for Wagtail Search? - Wagtail Space 2025](https://www.youtube.com/watch?v=LglWFsqIu3E\&list=PLfwZ-fob20cPI9_fnG_ULYIdOS5TKP1IZ\&index=26) by Matt Westcott.

### Podcasts

* [Podcast.\_\_init\_\_ Episode 58 - Wagtail with Tom Dyson](https://www.pythonpodcast.com/episodepage/episode-58-wagtail-with-tom-dyson) - In this episode Tom Dyson explains how Wagtail came to be created, what sets it apart from other options, and when you should implement it for your projects.
* [Django Chat: Wagtail CMS - Tom Dyson](https://django-chat.simplecast.com/episodes/wagtail-cms-tom-dyson) - An interview with Tom Dyson on Wagtail, the leading Django-based CMS used by tens of thousands of organizations including Google, NASA, and the British NHS.
* [Django Chat: Dawn Wages](https://djangochat.com/episodes/wagtail-react-gatsby-dawn-wages-RaD8k37m) - An interview with Dawn Wages, a core Wagtail team member. Discussion about Wagtail, React and Gatsby.
* [Django Chat: Thibaud Colas](https://djangochat.com/episodes/thibaud-colas-2025-dsf-board-nominations) - An interview with a core team member of Wagtail, discussing the current status of Django, upcoming DSF Board elections, Wagtail roadmap & community opportunities.

### Videos

* [Learn Wagtail](https://learnwagtail.com/) - Regular video tutorials about all aspects of Wagtail.
* [Wagtail screencasts: Creating and displaying pages in Wagtail](https://www.youtube.com/watch?v=o_dFgr8HZYU) - This video will show you how to create and display pages using the Wagtail CMS.
* [Draftail extensions – custom entities tutorial](https://www.youtube.com/watch?v=nCMgoTerEb4) - Step-by-step tutorial to make extensions for Draftail.
* [Wagtail Wednesdays #01 - Adding Help Text to Improve Wagtail Editor Experience](https://www.youtube.com/watch?v=ciYNMcv3lE0) - Catherine talks you through the steps you can take to add some useful supplementary text fields to the Wagtail admin.
* [Wagtail Wednesdays #02 - Customising Rich Text Features in Wagtail](https://www.youtube.com/watch?v=ei7ot_Wry3o) - Catherine talks you through the steps you can take to customise your rich text editors to control which features are available to your content editors.
* [Wagtail Wednesdays #03 - Using tabs to create a cleaner admin interface](https://www.youtube.com/watch?v=uZc0aZrHtQw) - Chris talks you through using tabs to organise fields.
* [Wagtail Wednesdays #04 - Organising Images and Documents using Wagtail Collections](https://www.youtube.com/watch?v=HGXHtFpLDCA) - Kieran talks you through the process of organising your images and documents into collections.
* [Wagtail Wednesdays #05 - How to organise your fields and streamline the editor experience](https://www.youtube.com/watch?v=CedcZmQ9KHs) - Chelsea talks you through the process of organising your fields to make it easier to manage them and streamline the editor experience.
* [Wagtail Wednesdays #06 - Creating & using custom settings in your wagtail site](https://www.youtube.com/watch?v=KJWCGq3IRNc) - Chris talks you through setting up and using custom site settings.
* [Wagtail Wednesdays #07 - How to Enable the Wagtail Styleguide](https://www.youtube.com/watch?v=_CfU9UivYPI) - It’s a really helpful resource that takes no time at all to enable and it allows you to check your components against the guidelines and shows all the available Wagtail icons.
* [How to Deploy Wagtail to Google App Engine](https://www.youtube.com/watch?v=uD9PTag2-PQ) - Focus is Google Cloud Platform but a great introduction on how to get Wagtail up and running in their PAAS.

### Books

* [The Definitive Guide to Next.js and Wagtail](https://leanpub.com/the-definitive-guide-to-nextjs-and-wagtail/) - Build a Jamstack web app with Next.js and Wagtail CMS.
* [Build a Blog With Wagtail CMS (3.0.0)](https://leanpub.com/buildblogwithwagtailcms) - This book will teach you how to build a modern blog with Wagtail CMS.
* [Build SPA with React and Wagtail (2.0.0)](https://leanpub.com/react-wagtail) - This book will teach you how to build a SPA (single-page application) with React and Wagtail CMS.
* [Build a Blog with React (SSR) and Wagtail](https://leanpub.com/react-wagtail-ssr) - This book will teach you how to build a blog with React, Wagtail CMS and SSR (Server-Side Rendering).

### Showcases

* [Made with Wagtail](https://madewithwagtail.org/) - A showcase of sites and apps made with Wagtail CMS.
* [Contributed apps and website code](https://github.com/wagtail/wagtail/wiki/Contributed-apps-and-website-code) ⭐ 20,132 | 🐛 1,006 | 🌐 Python | 📅 2026-02-10 - A provisional directory of third-party contributed Wagtail websites and apps.

### Lists

* [PyPI - Python Package Index](https://pypi.org/search/?q=Wagtail) - Wagtail packages on the Python Package Index.
* [Django Packages](https://djangopackages.org/grids/g/wagtail-cms/) - Wagtail projects and packages on Django Packages.

## For editors

* [How Do I Wagtail?](https://www.mozillafoundation.org/en/docs/how-do-i-wagtail/) - Mozilla's editor facing guide for how to use Wagtail's admin interface.
* [Wagtail Editor's manual](https://docs.wagtail.org/en/stable/editor_manual/index.html) - Wagtail documentation for editors
* [CCA Wagtail Editor Portal](https://portal.cca.edu/help/wagtail-documentation/) - User facing documentation for Wagtail by California College of the Arts
* [Caltech Wagtail Editor Portal](https://sites.caltech.edu/) - User facing documentation for Wagtail by Caltech
* [IoGT Wagtail CMS](https://cms-manual.goodinternet.org/en/) - User facing documentation for Wagtail by the IoGT (Internet of Good Things).

## Community

* [Wagtail Space](https://www.wagtail.space/) - Wagtail training sessions, Wagtail (lightning) talks and a Wagtail sprint. From March 13th until 15th 2019, Wagtail Space takes place in Arnhem, The Netherlands.
* [Wagtail updates on Telegram](https://telegram.me/wagtail) - Unofficial Telegram channel for general Wagtail updates.
* [Wagtail support on Telegram](https://telegram.me/wagtailcms) - Unofficial Telegram channel for support questions and discussions.

## Open-source sites

* [bakerydemo](https://github.com/wagtail/bakerydemo) ⭐ 1,063 | 🐛 42 | 🌐 Python | 📅 2026-02-11 – Next generation Wagtail demo, born in Reykjavík.
* [Consumer Financial Protection Bureau](https://github.com/cfpb/consumerfinance.gov) ⭐ 324 | 🐛 45 | 🌐 Python | 📅 2026-02-10 – The source code of the Wagtail-powered consumerfinance.gov is available here on GitHub.
* [Outreachy website](https://github.com/outreachy/website/) ⭐ 293 | 🐛 202 | 🌐 HTML | 📅 2026-02-08 - Website for Outreachy, who provide internships in open source and open science.
* [Federal Election Commission](https://github.com/fecgov/fec-cms) ⭐ 106 | 🐛 482 | 🌐 Python | 📅 2026-02-10 – The content management system (CMS) for the new Federal Election Commission website.
* [Secure the News](https://github.com/freedomofpress/securethenews) ⚠️ Archived – An automated scanner and web dashboard for tracking TLS deployment across news organizations.
* [Made with Wagtail](https://github.com/springload/madewithwagtail) ⭐ 90 | 🐛 31 | 🌐 Python | 📅 2026-01-07 - A showcase of sites and apps made with Wagtail CMS.
* [WesternFriend](https://github.com/WesternFriend/westernfriend.org) ⭐ 61 | 🐛 24 | 🌐 Python | 📅 2026-02-04 - community website with directory, ecommerce, and online subscription
* [SecureDrop](https://github.com/freedomofpress/securedrop.org) ⭐ 42 | 🐛 80 | 🌐 Python | 📅 2026-02-10 – Wagtail-powered website of the SecureDrop whistleblower document submission system.
* [Wagtail user guide](https://github.com/wagtail/guide) ⭐ 33 | 🐛 70 | 🌐 Python | 📅 2026-02-09 - A website to teach Wagtail to content editors, moderators and administrators.
* [Jordi Joan’s blog](https://github.com/jordij/jordijoan.me) ⭐ 20 | 🐛 3 | 🌐 Python | 📅 2022-12-27 – Personal blog site using Wagtail CMS.
* [NHS.UK Content Store](https://github.com/nhsuk-archive/nhsuk-content-store) ⚠️ Archived – NHS.UK content store and editing app.
* [Localore: Finding America](https://github.com/ghostwords/localore) ⭐ 19 | 🐛 0 | 🌐 Python | 📅 2018-07-18 – Wagtail-based CMS and Ansible playbooks for Localore: Finding America.
* [Digital Helsinki](https://github.com/City-of-Helsinki/digihel) ⚠️ Archived – City of Helsinki Digital Helsinki Wagtail CMS.
* [RTEI](https://github.com/okfn/rtei) ⭐ 16 | 🐛 9 | 🌐 Python | 📅 2022-12-15 – Right to Education Index website (OKFN).
* [OpenCanada.org](https://github.com/CIGIHub/opencanada) ⚠️ Archived – The opencanada.org website source.
* [dev.hel.fi](https://github.com/City-of-Helsinki/devheldev) ⚠️ Archived – City of Helsinki development site with Wagtail.
* [Project TIER](https://github.com/ProjectTIER/projecttier.org) ⭐ 13 | 🐛 43 | 🌐 Python | 📅 2024-07-11 – Teaching Integrity in Empirical Research.
* [BVSPCA](https://github.com/nfletton/bvspca) ⭐ 10 | 🐛 9 | 🌐 Python | 📅 2025-05-27 – Bow Valley SPCA website.
* [torchbox.com](https://github.com/torchbox/torchbox.com) ⭐ 8 | 🐛 6 | 🌐 Python | 📅 2026-02-09 – Wagtail build of Torchbox.com.
* [Table Tennis Wellington Business Class](https://github.com/jordij/bctt.nz) ⭐ 5 | 🐛 5 | 🌐 HTML | 📅 2022-11-22 – Website for the table tennis business league in Wellington NZ.
* [Adventure Capitalists](https://github.com/AdventureCapitalists/website) ⭐ 4 | 🐛 2 | 🌐 Python | 📅 2020-09-30 – Wagtail powered website for the world's only investment band.
* [WagtailParadise](https://github.com/abrahamrome/WagtailParadise) ⭐ 4 | 🐛 0 | 📅 2022-03-12 - demo Wagtail site showing common features and recipes
* [Penticon Public Library](https://github.com/danlerche/public-library-wagtailCMS) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-06 - An example public library website, originally created for the Penticton Public Library in Penticton, British Columbia, Canada.

## Contribute

Contributions are always welcome!
Please read the [contribution guidelines](origin/.github/CONTRIBUTING.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Springload](https://www.springload.co.nz/) has waived all copyright and related or neighboring rights to this work.
