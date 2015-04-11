Going to try to start using JSON. It seems to be the best balance between human readability and ease of parseing.
For reference, here is an example using a CSS comment:
```
{"snippet":[
  {"name":"css-comment-wrap"},
  {"language":"CSS"},
  {"title":"CSS Comment Wrap"},
  {"type":"wrap"},
  {"before":"/*"},
  {"after":"*/"}
  ]}
```
  
So the format is (note: this example is a "wrap" type comment:

```
{"snippet":[
  {"name":"<_filename minus extension_>"},
  {"language":"<_scripting/programming language_>"},
  {"title":"<_short description_>"},
  {"type":"<_block/wrap/dynamic_>"},
  {"before":"<_code before selection_>"},
  {"after":"<_code after selection_>"}
  ]}
```

_Raw text is also okay_, just come back later and format it if you can. We can't parse it in just any old format (unless it is just to be inserted as a block), and this way, we can script the changes of we need to change something about the syntax. 
