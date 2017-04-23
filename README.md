# FidoJS

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

// fido can bark out HTML
// fido can chew HTML tags
// fido does html

fidojs/fido-skill-html/fido.js
	fido.can("bark", htmlOut);
	fido.can("chew", htmlTags);
	fido.do("html", function() {...});
```

The "tags" are like a dog tag for the file... Name, address, etc...
