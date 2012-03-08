### Plugin to render gists in octopress

I wanted to improve the gist plugin because I didn't like rendering Markdown files as code.

The **gistapi** tag will now render markdown files inside your page while other files are still displayed in a code block.

The **gist** tag has been preserved and modified to use parameters for cacheing.

#### Installation

put *gist_tag.rb* file in **plugins directory**

#### Usage

``` markdown
{% gistapi 12345 %}
{% gistapi nocache %}
{% gistapi cache some_file.txt %}
```
