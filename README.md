# &lt;paper-spinner-text&gt;

> A bare minimum custom element starter-kit using [Polymer](http://www.polymer-project.org/).
>
> Like [Yeoman](http://yeoman.io/)? Use the [generator-element](https://www.npmjs.org/package/generator-element) instead.
>
> Looking for a working example? Check [hello-world-polymer](https://github.com/webcomponents/hello-world-polymer).

## Demo

[Check it live!](http://ryuheechul.github.io/paper-spinner-text)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install paper-spinner-text --save
```

Or [download as ZIP](https://github.com/ryuheechul/paper-spinner-text/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/paper-spinner-text/paper-spinner-text.html">
    ```

3. Start using it!

    ```html
    <paper-spinner-text></paper-spinner-text>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`active`      | *boolean*   | `false`      | activate spinner.
`hideText`    | *boolean*   | `false`      | hide text when spinner is activate.
`color`       | *string*    | `null`       | color for spinner.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/my-user/my-repo/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
