# Micro.blog Search Partial

![](https://github.com/gr36/search-partial/raw/main/docs/search-bar.png)

This plugin for micro.blog will allow you to add a search bar to any page you wish. 

## Set Up
Instal the plugin from Github by clicking design, edit theme, and then add new plugin.

Call the plugin anything you wish, copy in the URL from the Github page, and click Add Plugin.

### Add Partial
Add the partial to the page you wish this to show on, for example, I have placed this on my home page but you could do this wherever you like.

Simply add `{{ partial "search.html" . }}` to your page and the search bar will show as 100% width of the element it is placed in.

When searching, an HTML element will appear and show the results, linking to pages that contain the searched for words.

![](https://github.com/gr36/search-partial/raw/main/docs/search-results.png)

### Customise Search

You can custmies the number of results shown on your page by heading into plugin options and changing the default from 5.

![](https://github.com/gr36/search-partial/raw/main/docs/search-options.png)


## Styling

The styling of the search bar will be depend on your theme, I have added in some basic styling as follows.

``` 
    .field {
        width: 100%;
        height: 34px;
        border: 2px solid #eee;
        padding-left: 10px;
        margin-top: 20px;
        margin-bottom: 20px;
        border-radius: 11px;
    }
    
    #list_results {
        padding: 2rem;
        border-radius: 11px;
        box-shadow: rgba(60, 64, 67, 0.3) 0px 1px 2px 0px, rgba(60, 64, 67, 0.15) 0px 1px 3px 1px;
    
    }
```

`.field` is the search box itself.

`#list_results` is the results box that only shows when search results are found.

## Credits
The basis of this plugin came from Manton [search page plugin](https://github.com/microdotblog/plugin-search-page). 
