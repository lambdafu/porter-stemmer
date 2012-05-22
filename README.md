porter-stemmer
==============

JavaScript/AMD version of porter-stemmer.

The stemming algorithm expects the word to be all lower-case:

```js
require(["porter-stemmer/german"], function(porter){
word = "Läufer";
word = word.toLowerCase();
stem = porter.stemmer(word);
alert(stem);
});
```

german.js:
http://snowball.tartarus.org/otherlangs/german_javascript.txt

Author: Joder Illi

Copyright (c) 2010, FormBlitz AG  All rights reserved.

Implementation of the stemming algorithm from
http://snowball.tartarus.org/algorithms/german/stemmer.html
Copyright of the algorithm is: Copyright (c) 2001, Dr Martin
Porter and can be found at
http://snowball.tartarus.org/license.php

Redistribution and use in source and binary forms, with or
without modification, is covered by the standard BSD license.

