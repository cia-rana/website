---
title: InvalidTypeArg
layout: article
---
<!-- Copyright 2023 The Go Authors. All rights reserved.
     Use of this source code is governed by a BSD-style
     license that can be found in the LICENSE file. -->

<!-- Code generated by generrordocs.go; DO NOT EDIT. -->

```
InvalidTypeArg occurs when a type argument does not satisfy its
corresponding type parameter constraints.

Example:
 type T[P ~int] struct{}

 var _ T[string]
```

