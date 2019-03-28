# Hugo Learn Theme

This repository contains a theme for [Hugo](https://gohugo.io/), based on great [Grav Learn Theme](http://learn.getgrav.org/).

Visit the [theme documentation](https://learn.netlify.com/en/) to see what is going on. It is actually built with this theme.

## Main features

- Automatic Search
- Multilingual mode
- Unlimited menu levels
- Automatic next/prev buttons to navigate through menu entries
- Image resizing, shadow…
- Attachments files
- List child pages
- Mermaid diagram (flowchart, sequence, gantt)
- Customizable look and feel and themes variants
- Buttons, Tip/Note/Info/Warning boxes, Expand

## Extra Features for Naturalis

Taxonomies now are also automatically added to the navigation. This is done by
[extra code in the menu partial](https://github.com/naturalis/hugo-theme-naturalis/blob/df79612d9a5496265db7469113a0a7cdacabc40f/layouts/partials/menu.html#L28).

These are also added to the [json generated for search](https://github.com/naturalis/hugo-theme-naturalis/blob/df79612d9a5496265db7469113a0a7cdacabc40f/layouts/index.json#L13).

The breadcrumb for taxonomies is [also generated differently](https://github.com/naturalis/hugo-theme-naturalis/blob/df79612d9a5496265db7469113a0a7cdacabc40f/layouts/partials/header.html#L93).

These taxonomy pages can not use the next/prev buttons, so for taxonomy and terms they
[are no longer displayed](https://github.com/naturalis/hugo-theme-naturalis/blob/df79612d9a5496265db7469113a0a7cdacabc40f/layouts/partials/footer.html#L12). 


## Installation

Navigate to your themes folder in your Hugo site and use the following commands:

```
$ cd themes
$ git clone https://github.com/matcornic/hugo-theme-learn.git
```

Check that your Hugo version is minimum `0.25` with `hugo version`.

![Overview](https://github.com/matcornic/hugo-theme-learn/raw/master/images/tn.png)

## Usage

- [Visit the documentation](https://learn.netlify.com/en/)

## Download old versions (prior to 2.0.0)

If you need old version for compatibility purpose, either download [theme source code from releases](https://github.com/matcornic/hugo-theme-learn/releases) or use the right git tag. For example, with `1.1.0` 

- Direct download way: https://github.com/matcornic/hugo-theme-learn/archive/1.1.0.zip
- Git way:

```shell
cd themes/hugo-theme-learn
git checkout tags/1.1.0
```

For both solutions, the documentation is available at https://github.com/matcornic/hugo-theme-learn/releases/download/1.1.0/hugo-learn-doc-1.1.0.zip

## Credits

Many thanks to [@vjeantet](https://github.com/vjeantet/) for the fork [docdock](https://github.com/vjeantet/hugo-theme-docdock). The v2 of this theme is mainly based on his work!
