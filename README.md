Octopress highlight plugin
=========================

Octopress is a great platform based on Jekyll. It can help you in create a
great static blog or website.

I introduced a plugin that helps you in highlighting a piece of text

## Intallation

You can clone this repository into your octopress plugin directory or move the highlight.rb file in the plugin directory.
Add this in your sass/custom/_layout.scss file.

  span.fluo {
    background-color: #FEDB7C;
    padding: 3px 1px 3px 1px;
    text-shadow: 0 -1px 1px #DAC793;
  }

## Usage

{% highlight this is a great piece of wisdom %}, this is not.

Enjoy, it!
