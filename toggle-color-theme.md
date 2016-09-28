# Toggle color theme button
To add the **toggle light/dark theme** button from the demo to the sidebar of your forum, add the following code<br>
to a custom wiget (e.g.: *CUSTOM CODE WIDGET 1*) and enable the widget in the sidebar.

## The code:
```javascript
<script>
  var darkThemeCSS = document.createElement('link');
  darkThemeCSS.id = 'darkThemeCSS';
  darkThemeCSS.href = './ext/eles/coreframe/styles/eles/theme/colors.css.php?theme=dark'
    + '&primary=rgb%2817%2C+180%2C+165%29'
    + '&accent=rgb%28221%2C+76%2C+90%29'
    + '&text=rgb%28161%2C+192%2C+206%29'
    + '&textalt=rgb%28241%2C+241%2C+241%29'
    + '&border=rgb%2882%2C+98%2C+105%29'
    + '&white=rgb%2859%2C+74%2C+82%29'
    + '&black=rgb%28203%2C+203%2C+203%29';
  darkThemeCSS.rel = 'stylesheet';
  darkThemeCSS.type = 'text/css';
  darkThemeCSS.media = 'screen';

  var isDarkTheme = (window.localStorage.getItem('isDarkTheme') === 'true');
  if (isDarkTheme) {
    document.head.appendChild(darkThemeCSS);
    document.body.classList.add('dark');
    document.body.classList.remove('light');
  };

  function testDarkTheme() {
    if (!isDarkTheme) {
      document.head.appendChild(darkThemeCSS);
      document.body.classList.add('dark');
      document.body.classList.remove('light');
    } else {
      document.getElementById('darkThemeCSS').remove();
      document.body.classList.add('light');
      document.body.classList.remove('dark');
    }
    isDarkTheme = !isDarkTheme;
    window.localStorage.setItem('isDarkTheme', isDarkTheme);
  }
</script>

<div style="height: 36px;">
  <button type="button" class="button button1 theme-toggler" onclick="testDarkTheme()">
    <i class="fa fa-eye fa-fw"></i>
    Toggle Dark Color Theme
  </button>
</div>
<div class="widget-space" style="padding-top: 30px;"></div>
