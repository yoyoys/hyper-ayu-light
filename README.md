# Ayu Light Hyper Theme
Ayu (light special) for Hyper
Forked from [hyper-ayu-light](https://www.github.com/weirdpattern/hyper-ayu-light)

I've just add black color for more readable.
Here's the screenshot.  
![Screenshot](https://raw.githubusercontent.com/yoyoys/hyper-ayu-light/master/screenshot.png)

## Installation
1. Open Hyper's preferences with `Cmd +`, (or manually at `~/.hyper.js`).
2. Update your list of plugins to include `hyper-ayu-light-special`, like this:

```javascript
  plugins: [
    'hyper-ayu-light-special'
  ]
```

3. Fully reload Hyper (`Cmd + Shift + R`)

## Configuration
You can decide whether to display the tab border or not using the following configuration:

```javascript
  config: {
    ayu: {
      // true will hide all borders; false will display them.
      noBorder: boolean 

      // true will display the tab border; false will hide them.
      // on macOS, this is the opposite of noBorder.
      showTabBorder: boolean,

      // Windows only
      // true will display the header border; false will hide it.
      showHeaderBorder: boolean,

      // Windows only
      // controls the background color of the header
      // e.g #FF00DD, rgb(254, 254, 254), red
      headerBackgroundColor: 'string',

      // Windows only
      // controls the foreground color of the header (title and windows controls)
      // e.g #FF00DD, rgb(254, 254, 254), red
      headerForegroundColor: 'string'
    }
  }
```

## Related

- [Hyper](https://hyper.is/)
- [Ayu for Sublime Text](https://github.com/dempfi/ayu)
- [Ayu for Vim](https://github.com/ayu-theme/ayu-vim)
- [Ayu (dark) for Hyper](https://github.com/licatajustin/hyper-ayu)
- [Ayu (mirage) for Hyper](https://github.com/weirdpattern/hyper-ayu-mirage)
- [Ayu (light) for Hyper](https://www.github.com/weirdpattern/hyper-ayu-light)

## License
MIT © Patricio Trevino, Yoyo Young
