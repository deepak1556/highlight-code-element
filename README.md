# &lt;highlight-code&gt;

A web component wrapper to highlight code snippets in any webpage using ```highlighterJs```.

> Maintained by [Robo](https://github.com/deepak1556).

## Demo

> [Check it live](http://deepak1556.github.io/highlight-code-element).

## Usage

1. Import Web Components' polyfill:

   ```html
   <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130711/polymer.min.js"></script>
   ```

2. Import Custom Element:

   ```html
   <link rel="import" href="src/highlight.html">
   ```

3. Start using it!

   ```html
   <highlight-code></highlight-code>
   ```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`height`      | *int*                  | `500`               | The height of snippet container
`width`      | *int*          | `500`               | THe width of snippet container
`tabreplace`   | *string*                     | `   `               | Overwrite default tab spaces '4'


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.0.1 August 19, 2013
  * Started project using [highlighter-element](https://github.com/deepak1556/highlighter-element)

## License

[MIT License](http://opensource.org/licenses/MIT)
