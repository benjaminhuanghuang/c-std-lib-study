provide a definition of the macro assert. 

Terminate execution abnormally and write a suitably revealing message to the standard error stream.

```
#include <assert.h>
.....
assert(0 <= idx && idx < sizeof a / sizeof a[O]); /* a[idx] is now safe */

```

turn assertions on:
```
#undef NDEBUG
#include <assert.h>
```
turn assertions off:
```
#define NDEBUG
#include <assert.h>
```