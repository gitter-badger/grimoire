Takes a body of expressions and yields a future object that willinvoke the body in another thread, and will cache the result andreturn it on all subsequent calls to deref/@. If the computation hasnot yet finished, calls to deref/@ will block, unless the variant ofderef with timeout is used. See also - realized?.