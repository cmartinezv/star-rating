# &lt;star-rating&gt;

A Polymer element for star ratings

> Maintained by [Carlos Martinez](https://github.com/cmartinezv).

## Demo

> [Check it live]( http://cmartinezv.github.io/webcomponents/star-rating).

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

## Setup

In order to run it locally you'll need a basic server setup.

1. Install [NodeJS](http://nodejs.org/download/).
2. Install [GruntJS](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g grunt-cli
    ```

3. Install local dependencies:

    ```sh
    $ npm install
    ```

4. Run a local server and open `http://localhost:8000`.

    ```sh
    $ grunt connect
    ```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`stars`      | *number*                  | `5`               | Number of stars
`rate`      | *number*                  | `0`               | Default number of stars selected


## License

[MIT License](http://opensource.org/licenses/MIT)