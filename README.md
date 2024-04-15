# Micro.blog Search Partial

![](https://github.com/gr36/search-partial/raw/main/docs/search-bar.png)

This plugin for micro.blog will allow you to add a search bar to any page you wish. 

## Set Up

Instal the plugin from github by clicking design, edit theme, and then add new plgin.

Call the plugin anything you wish, copy in the URL from the github page, and click Add Plugin.

### Add Partial

Add the patialal to the page you wish this to show on, for example, I have placed this on my [home page](https://gregmorris.co.uk).

To do this add `{{ partial "search.html" . }}` to your page.

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

`.field` is the searchbox itself.

`#list_results` is the results box that only shows when search results are found.

## Credits
The basis of this plugin cam from Mantons Search page plugin, 
