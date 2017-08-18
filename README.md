# HN comments
Get comments from [Hacker News](https://news.ycombinator.com) with javascript for your static (or not) site

## Usage

Create an element with `id="hnComments"` in your markup. 
It should have a _data-hn-id_ attribute whose value is the id of the post you made on hn, e.g. 

```
https://news.ycombinator.com/item?id=15044479
                                     ^^^^^^^^
                                     THIS IS THE ID
```

The comments will be inserted after that element.

Example : 

``` html
<h4 id="hnComments" style="margin-top:4em" data-hn-id="15044479">
    Comments from <a href="https://news.ycombinator.com/item?id=15044479">HN</a>
    <a href="https://news.ycombinator.com/item?id=15044479">Discuss</a>
</h4>
<script src="assets/js/hn.js></script>
```
