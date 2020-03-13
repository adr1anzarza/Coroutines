Kotlin, as a language, provides only minimal low-level APIs in its standard library to enable various other 
libraries to utilize coroutines. Unlike many other languages with similar capabilities, `async` and `await`
are not keywords in Kotlin and are not even part of its standard library. Moreover, Kotlin's concept
of _suspending function_ provides a safer and less error-prone abstraction for asynchronous 
operations than futures and promises.  

`kotlinx.coroutines` is a rich library for coroutines developed by JetBrains. It contains a number of high-level 
coroutine-enabled primitives that this guide covers, including `launch`, `async` and others. 

This is a guide on core features of `kotlinx.coroutines` with a series of examples, divided up into different topics.

In order to use coroutines as well as follow the examples in this guide, you need to add a dependency on `kotlinx-coroutines-core` module.

## Table of contents

* [Basics](../Coroutines/kotlin-coroutines-master/README.md)

## Additional references

* [Coroutines design document (KEEP)](https://github.com/Kotlin/kotlin-coroutines/blob/master/kotlin-coroutines-informal.md)
* [Full kotlinx.coroutines API reference](https://kotlin.github.io/kotlinx.coroutines)

## Where to learn more

* [Advanced Coroutines with Kotlin Flow and LiveData codelab](https://codelabs.developers.google.com/codelabs/advanced-kotlin-coroutines/index.html#0)
* [Coroutines guide](https://github.com/Kotlin/kotlinx.coroutines/blob/master/docs/coroutines-guide.md)
* [Cómo mejorar el rendimiento de la app con las corrutinas de Kotlin](https://developer.android.com/kotlin/coroutines)
* [Adrian´s workshop](https://docs.google.com/presentation/d/1K_BUJ5Xjy7MmRbBSz7Esc-B9z5Ll08lfzrnGqS6rpWA/edit?usp=sharing)