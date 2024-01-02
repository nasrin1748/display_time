# display_time

<!doctype html>
<html>
    <head>
        <title id="header-title"></title>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width,initial-scale=1" />
        <link rel="icon" type="image/png" href="./favicon.png" />
        <link
            rel="stylesheet"
            href="https://pyscript.net/latest/pyscript.css"
        />
        <script defer src="https://pyscript.net/latest/pyscript.js"></script>

        <link rel="stylesheet" href="./assets/css/examples.css" />
    </head>

    <body>

         <div id="Button Example">
            <h3>Button Example</h3>
            <button
                type="submit"
                id="btn-load"
                class="py-button"
                py-click="loadFromURL()"
            >
                Load
            </button>
        </div>

        <div id="output" hidden>
            <h3>Output</h3>
            <div id="output"></div>
        </div> 
        <py-script>
        from datetime import datetime
        def loadFromURL():
            now = datetime.now()
            print(now)
        </py-script>
    </body>
</html>


