# Spielwiese

Eine ganz leere Spielwiese? Oh, wie schön.

Da könnte man:

- Eine Liste machen
- Unsinn hinschreiben.
- `inline Code quoten`

```javascript
"use strict";

module.exports = function subdirs(req, res, next) {
  res.locals.wikisubdirs = [];
  next();
}
```

Ein Wiki also, na dann schauen wir mal wie gut das Einbinden von Bildern funktioniert:

![Alt text](http://upload.wikimedia.org/wikipedia/commons/thumb/9/9e/Wikipedia-logo-v2-de.svg/200px-Wikipedia-logo-v2-de.svg.png)
und was ist mit `C0DE`?

    int i=0;
    i++;
    {
        // Nothing in here
    }

### Interne Links
Auf jeder Spielwiese befindet sich auch ein ordentliches [Klettergerüst](klettergeruest). Auch eine [Wippe](./wippe) ist gern gesehen. Und ein [Sandkasten](/wiki/spielwiese/sandkasten) darf auch nicht fehlen.

### Externe Links
Man kann in ein anderes [Wiki](/wiki/hilfe) verlinken.

### Tabellen gehen auch:

| Tables        | Are           | Cool  |
| -------------|-------------|-----|
| Feld | Stärke | Kann |
| Auch      | Schön      |   Sein |

##Listen:
1. First ordered list item
2. Another item
  * Unordered sub-list. 
    * Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
  1. Ordered sub-list
4. And another item.

   You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

   To have a line break without a paragraph, you will need to use two trailing spaces.  
   Note that this line is separate, but within the same paragraph.  
   (This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)
1. finally
* Unordered list can use asterisks
* Unordered list can use asterisks
* Unordered list can use asterisks
- Or minuses
+ Or pluses