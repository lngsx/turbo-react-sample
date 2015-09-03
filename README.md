# turbo-react-sample
The sample site from its readme
[https://github.com/ssorallen/turbo-react](https://github.com/ssorallen/turbo-react)

### Plain HTML and Other Frameworks

1. Get turbo-react via NPM or download the latest release from GitHub:

    ```sh
    $ npm install turbo-react
    ```
   
   or

    ```sh
    $ curl https://raw.githubusercontent.com/ssorallen/turbo-react/tree/v0.8.0/public/dist/turbo-react.min.js
    ```

2. Include turbo-react in the `<head>` of each page of the site after
   Turbolinks:

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        ...
        <script src="path/to/turbolinks.js"></script>
        <script src="path/to/turbo-react.min.js"></script>
      </head>
      <body>
        ...
      </body>
    </html>
    ```