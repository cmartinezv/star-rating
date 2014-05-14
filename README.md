# &lt;star-rating&gt;

A Polymer element for star ratings

> Maintained by [Carlos Martinez](https://github.com/cmartinezv).

## Demo

> [Check it live]( http://cmartinezv.github.io/star-rating).

## Installation

Using [Bower](http://bower.io), run:

```shell
bower install star-rating
```

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.1.4/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="src/star-rating.html">
    ```

3. Start using it!

    ```html
    <star-rating></star-rating>
    ```

## Examples

Basic usage:

```
<star-rating></star-rating>
```

Custom number of stars:

```
<star-rating stars="10"></star-rating>
```

Default rate selected:

```
<star-rating stars="10" rate="3"></star-rating>
```

Add your custom styles:

```
<star-rating stars="10" rate="3" class="custom-class"></star-rating>
```


## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`stars`      | *number*                  | `5`               | Number of stars
`rate`      | *number*                  | `0`               | Default number of stars selected


## License

[MIT License](http://opensource.org/licenses/MIT)