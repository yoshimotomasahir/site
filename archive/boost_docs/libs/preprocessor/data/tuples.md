# Tuples

*タプル*は、丸カッコの中に、要素を単純にコンマで区切って並べたものである。
例えば、

```cpp
(a, b, c)
```

は `a`、`b`、`c` の三要素からなる*タプル*である。

*タプル*は速く、また簡単に使える。
しかし、*タプル*へのすべてのアクセスにはそのサイズが必要となる。

*タプル*の要素は `BOOST_PP_TUPLE_ELEM` により展開される。

## Primitives

- [`BOOST_PP_TUPLE_ELEM`](../ref/tuple_elem.md)

