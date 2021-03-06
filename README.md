# FidoJS

Fetches files, sniffs for strings, chews on them, and barks out documentation.

```js
// fido can fetch with glob

fidojs/fido-skill-glob/fido.js
	fido.can("fetch", withGlob);

// fido can sniff mustache files

fidojs/fido-skill-mustache/fido.js
	fido.can("sniff", mustacheFiles);

// fido can sniff JavaScript files
// fido can chew JavaScript tags
// fido can "html" the passed dependencies and templates

fidojs/fido-skill-js/fido.js
	fido.can("sniff", jsFiles);
	fido.can("chew", jsTags);
	fido.can("html", {dependencies,templates});

// fido can chew HTML tags
// fido can bark out HTML
// fido will do html

fidojs/fido-skill-html/fido.js
	fido.can("chew", htmlTags);
	fido.can("bark", htmlOut);
	fido.do("html", function() {...});
```

A "tag" is the "dog tag" of a file or function; the name, address, parent, etc...

![](docson.jpg)
