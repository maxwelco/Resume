This reprex appears to crash R.
See standard output and standard error for more details.

<details style="margin-bottom:10px;">
<summary>Standard output and standard error</summary>

``` sh
Quitting from lines 41-43 (Untitled_reprex.Rmd) 
Error in py_call_impl(callable, dots$args, dots$keywords) : 
  AttributeError: 'module' object has no attribute '__import__'

Detailed traceback: 
  File "/Library/Frameworks/R.framework/Versions/4.0/Resources/library/reticulate/python/rpytools/loader.py", line 13, in initialize
    _import = builtins.__import__

```

</details>
