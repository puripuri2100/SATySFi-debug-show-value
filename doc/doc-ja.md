# 使い方

値がどのようになっているかを文字列化することで、確認できるようになります。

[assert-eq](https://github.com/puripuri2100/SATySFi-assert-eq)と一緒に使うことでテストを行いやすくなります。

# 提供関数

モジュール名：`DebugShowValue`

- `show-int : int -> string`
- `show-string : string -> string`
- `show-bool : bool -> string`
- `show-length-pt : length -> string`
- `show-length-mm : length -> string`
- `show-length-inch : length -> string`
- `show-unit : unit -> string`
- `show-tuple : ('a -> string) -> 'a list -> string`
- `show-list : ('a -> string) -> 'a list -> string`
- `show-opt : ('a -> string) -> 'a option -> string`
- `show-point : point -> string`
- `show-color : color -> string`
- `show-opt-list : ('a -> string) -> ('a option) list -> string`
