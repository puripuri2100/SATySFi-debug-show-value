
「リストの中を作ったは良いが、中がどういう順番に何が並んでいるのかを確認したい」という時に使える便利なものです。

module : `DebugShowValue`

functions :

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


---

This package released under [the MIT license](https://github.com/puripuri2100/SATySFi-debug-show-value/blob/master/LICENSE).

---
(c) Naoki Kaneko (a.k.a. puripuri2100) 2019
