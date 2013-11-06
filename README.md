explain all the things !!
=========================

```php
/*
* explain some code
* @param code the file or code to explain
* @param type the type of $code EXPLAIN_FILE or EXPLAIN_STRING
* @return array
*/
function explain($code, $type = EXPLAIN_FILE);
/*
* explain_opcode
* @param opcode the opcode
* @return string
*/
function explain_opcode($opcode);
/*
* explain_optype
* @param optype the optype
* @return string
*/
function explain_optype($optype);
```

<img src="https://raw.github.com/krakjoe/explain/master/explain.png" alt="screenshot"/>

See explain.php for helpingz ... [![Build Status](https://travis-ci.org/krakjoe/explain.png?branch=master)](https://travis-ci.org/krakjoe/explain)
