## starname

Gets you a random star name, names taken from [Wikipedia](https://en.wikipedia.org/wiki/List_of_proper_names_of_stars)

### Installation

```bash
yarn add starname
```

### Usage

```javascript
import starname, { constellation } from 'starname'

starname()
// Albireo

constellation()
// Corona Borealis
```

### Upgrading from 1.x

1.x returned constellation names, not star names. The default export now returns real star names. Use `constellation()` if you relied on the old names.
