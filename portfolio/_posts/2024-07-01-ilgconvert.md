---
layout: default
title: Interlinear gloss converter
tags: development linguistics
---

A handy Flask application to convert linguistic examples into and between different styles of LaTeX markup.

For example, convert an interlinear example between plain text, Linguex, gb4e, or ExPex formats.

```txt
El    ejemplo.
DEF.M example
The example.
```

```tex
\exg. El    ejemplo. \\
      DEF.M example \\
      The example.
```

```tex
\begin{exe}
\ex
\gll El    ejemplo. \\
     DEF.M example \\
\glt The example.
\end{exe}
```

```tex
\ex
\begingl
\gla El    ejemplo. //
\glb DEF.M example //
\glft The example. //
\endgl
\xe
```

## Links

* [Check out the application](https://ilgconvert-db94afc72fff.herokuapp.com/)
<!-- FIX: repo needs publishing
* [View `ilgconvert_app` source code](https://github.com/caforbes/ilgconvert_app) -->