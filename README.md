# Mélancolique Nocturne

A curated color palette evoking the atmosphere of a pensive night. Six shades of blue trace a journey from the deepest dark to barely-there light — from melancholy to catharsis.

## Colors

| Name | Hex | RGB |
|---|---|---|
| Midnight Shadow | `#1a1a2e` | 26, 26, 46 |
| Deep Indigo | `#16213e` | 22, 33, 62 |
| Melancholy Blue | `#4a5d7a` | 74, 93, 122 |
| Moonlit Gray | `#6b7b95` | 107, 123, 149 |
| Catharsis | `#9bb5d6` | 155, 181, 214 |
| Distant Stars | `#d4e4f0` | 212, 228, 240 |

## Usage

### CSS

```css
:root {
  --midnight-shadow: #1a1a2e;
  --deep-indigo:     #16213e;
  --melancholy-blue: #4a5d7a;
  --moonlit-gray:    #6b7b95;
  --catharsis:       #9bb5d6;
  --distant-stars:   #d4e4f0;
}
```

### SCSS

```scss
$midnight-shadow: #1a1a2e;
$deep-indigo:     #16213e;
$melancholy-blue: #4a5d7a;
$moonlit-gray:    #6b7b95;
$catharsis:       #9bb5d6;
$distant-stars:   #d4e4f0;
```

### Tailwind CSS

```js
// tailwind.config.js
module.exports = {
  theme: {
    extend: {
      colors: {
        'midnight-shadow': '#1a1a2e',
        'deep-indigo':     '#16213e',
        'melancholy-blue': '#4a5d7a',
        'moonlit-gray':    '#6b7b95',
        'catharsis':       '#9bb5d6',
        'distant-stars':   '#d4e4f0',
      },
    },
  },
};
```

## Development

```bash
npm install
npm run dev
```

## License

GNU AGPL-3.0
