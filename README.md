# The Raleigh Tailor 
## theraleightailer.com


### Setup
1. First, this is a [Hugo](https://gohugo.io/) site so you'll need hugo installed on your machine to do local dev work.
1. This site uses the [Hugo Scroll](https://github.com/janraasch/hugo-scroll) theme.  The theme is setup as a git "submodule".  
    * If you already have this git repository cloned locall`y, run these commands to install the theme submodule:
        ```
        git submodule init
        git submodule update
        ```
    * Alternatively, you can clone this repo and all submodules with this command:
        ```
        git clone --recurse-submodules git@github.com:davidpenner/theraleightailor
        ```

### Local Development

* Nothing under `themes/hugo-scroll` should be changed.  If you need to override a file in the theme, you should make a copy of that file from the theme and edit that copy:
    ```
    cp themes/hugo-scroll/layouts/partials/footer.html layouts/partials/
    ```
* run `hugo server` and open `http://localhost:1313` in your browser to run the live development.