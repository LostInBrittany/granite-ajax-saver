[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/LostInBrittany/granite-ajax-saver)

# granite-ajax-saver

> A lightweight element to save the response from an AJAX call into a file on the local filesystem
>
> Hybrid Polymer element, 1.x-2.x ready

## Doc & demo

[https://lostinbrittany.github.io/granite-ajax-saver](https://lostinbrittany.github.io/granite-ajax-saver)


## Usage example

<!---
```
<custom-element-demo>
  <template>
    <style>
      .clickHere {
        border-radius: 2px;
        padding: 10px;
        background-color: #4285f4;
        color: white; 
      }
    </style>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="granite-ajax-saver.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<granite-ajax-saver 
    url="./demo/anExampleFileToLoad.txt">
    <div class="clickHere">Click here to save the content of `./demo/anExampleFileToLoad.txt` to a file</div>
</granite-ajax-saver>
```

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install LostInBrittany/granite-ajax-saver --save
```

Or [download as ZIP](https://github.com/LostInBrittany/granite-ajax-saver/archive/gh-pages.zip).## Usage

1. Import Web Components' polyfill (if needed):

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/granite-ajax-saver/granite-ajax-saver.html">
    ```

3. Start using it!

    ```html
    <granite-ajax-saver text="A new file will be created with this content">
        <div class="clickHere">Click here to save a file</div>
    </granite-ajax-saver>
    ```


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](http://opensource.org/licenses/MIT)