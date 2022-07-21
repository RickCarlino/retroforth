
~~~
'=====_alloc s:put nl
[ #200 mem:alloc #2 ] a:make 'foo const
:region foo #0 a:fetch foo #1 a:fetch ;
'=====_set s:put nl
region #123 mem:set
'=====_get s:put nl
dump-stack
region mem:get
~~~