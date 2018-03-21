# Ghost-Appearance
Simple snippet to add zoom on posts images for Ghost 0.11.11

### Preview
![Appearance for Ghost (preview)](https://raw.githubusercontent.com/bZez/Ghost-Appearance/master/appearance-for-ghost-preview.gif)

#### Usage
* ###### CDN: `<script src="http://cdn.sambzez.com/js/appearance.min.js"></script>`

      <script>
      $(function(){
        appearance();
      });
      </script>

* ###### Config:
You can set the margin-top and margin-left with: `appearance(X,Y)` where X = Margin-top & Y = Margin-left in percent.

    $(function(){
        appearance(10,10);
    });
    </script>
