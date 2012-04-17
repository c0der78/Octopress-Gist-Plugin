### Plugin to render gists in octopress

I wanted to change the gist plugin to not render Markdown files as code, and let the site display them as HTML

The **gistapi** tag will use the gist API.  It can now detect file types.

The **gist** tag has been preserved and modified to add parameters for cacheing.

#### Installation

put *gist_tag.rb* file in **plugins directory**

#### Usage

``` markdown
{% gistapi 12345 %}
{% gistapi 12345 nocache %}
{% gistapi 12345 cache some_file.txt %}
```
