## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/elkdashbeardotcom/CoinBox/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
<!DOCTYPE html>
<html lang="en">
    <head>

        <title>Coins.js</title>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, user-scalable=no, minimum-scale=1.0, maximum-scale=1.0">
        
        <!-- Stylesheets -->
        <link rel="stylesheet" href="css/game.css">

        <!-- three.js -->
        <script type="text/javascript" src="js/three.js"></script>
        <script type="text/javascript" src="js/libs/stats.min.js"></script>
        <script type="text/javascript" src="js/libs/dat.gui.min.js"></script>
        
        <!-- Physics -->
        <script type="text/javascript" src="js/physics/physi.js"></script>
        <script>
            Physijs.scripts.worker = '/assets/js/physics/physijs_worker.js';
            Physijs.scripts.ammo = '/assets/js/physics/ammo.js';
        </script>
        
        <!-- Shaders -->
        <script src="js/shaders/CopyShader.js"></script>
        <script src="js/shaders/SMAAShader.js"></script>

        <!-- Postprocessing -->
        <script src="js/postprocessing/EffectComposer.js"></script>
        <script src="js/postprocessing/SMAAPass.js"></script>
        <script src="js/postprocessing/RenderPass.js"></script>
        <script src="js/postprocessing/MaskPass.js"></script>
        <script src="js/postprocessing/ShaderPass.js"></script>
    </head>
    <body>
        
        <!-- Overlay -->
        <div id="overlay">

            <!-- Loading! -->
            <div id="loader" style="display: none;">
                <img src="textures/loader.gif">
                <h2>Loading <span style="color: #F5C715;">Coins</span>.js</h2>
            </div>

            <div id="coin-slot" onclick="createCoin(randomRange(-40,40),randomRange(80,100),randomRange(-20,-100));">
                <img src="textures/coin_slot.png">
            </div>

        </div>

        <!-- Container for game -->
        <div id="viewport"></div>

        <!-- Coins.js -->
        <script type="text/javascript" src="js/game.js"></script>
        
    </body>
</html>
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/elkdashbeardotcom/CoinBox/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
