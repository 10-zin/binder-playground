# binder-playground
An experimental repository for making mybinder work with ines/juniper

## Binder Output

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/10-zin/binder-playground/HEAD)

<html>
    <head>
        <title>Your website</title>
    </head>
    <body>
        <pre>
        <pre data-executable>
            print('hello world!')
        </pre>
        <script src="juniper.min.js"></script>
       <script>new Juniper({ repo: 'ines/juniper' })</script>
    </body>
</html>