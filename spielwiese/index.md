# Spielwiese

Eine ganz leere Spielwiese? Oh, wie schön.

Da könnte man:

- Eine Liste machen
- Unsinn hinschreiben.
- `inline Code quoten`

```
"use strict";

module.exports = function subdirs(req, res, next) {
  res.locals.wikisubdirs = [];
  next();
};
```