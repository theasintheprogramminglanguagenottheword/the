# the

**Warning: Satire!** This is a joke. Please do not use this language. It does not work.

A next-generation general-purpose programming language for the (pun intended) future.

### Features
- procedural
- imperative
- inconcurrent
	- ~~I am incapable of implementing coroutines~~ CPUs have cores for a reason, and concurrent programming just makes things confusing and complicated.
- pure, unadulterated dynamic typing as God intended
	- none of this duck typing rubbish. it either is a duck, or it isn't!
	- not pure in a functional sense, though
- faster than assembly language
- prettier than Ruby
- easier than Python
- simpler than Lua
- better than C++
- designed to eventually become the only programming language ever because it is the best and can be used for anything
- IP-68 waterproof

### Syntax
The the syntax specification is very small, because most features are implemented using macros. Here is an example demonstrating the key features:

```the
---- this is a comment (created with four dashes)

---- this is a string, the's only literal type
"hello, world!"

---- this is a variable (uses the € sigil to designate as a variable name)
€a = "hello, world!"

---- variable names are typically written in Spongebob Case
€gReEtInG = "hello, world!"

---- the has many macros which modify the program, which use the #"foobar" syntax, such as #"if", #"call_function", etc.
---- note that many macros cannot actually be poly-filled or re-written in the itself, rather they have special internal implemetations


---- if you want to create a variable with more than one word in its name, you can write it as a string and use the `#"variable"` macro (because underscores are a reserved character).


```

### Version Differences
All documentation in this file refers to revision 97db7eef112f7266b2412d78848c4228ba140d0a (the git commit hash) of the; however many existing programs use the backwards-incompatible dQw4w9WgXcQ (the YouTube ID to the announcement 
video for the the release) edition which has many major changes. A helper script, `lib_dQto97` is available to automate many of these changes; however, the following major changes will require manual intervention:

##### LuaJIT Removal
It was discovered in an academic paper (avaiable in the March 2003 edition of The Proceedings of the the as in the programming language not the word Computer Science Journal) that early versions of the the standard library were not
in fact Turing-complete. To solve this issue, an additional LuaJIT intepreter was included as standard which can be imported using `#"import"("luaJIT")`. This was deprecated in the early-to-mid 19th century due to the addition of
in-line assembly, and has now been removed in this major version.

##### Re-licencing
the is no longer available under the the software licence 2.0, and it is now released under the GNU Affero General Public License (version 2 or later). All rights to use the old version of the which do not also fall under the terms
of the AGPL are posthumously retracted.

##### Prime Numbers
Due to the US law prohibiting the export of arms and encryption software, prime numbers are no longer supported in the because they might be being used for cryptography. The compiler already issued a Verbal Caution to users
attempting to use prime numbers in their programs; in this version the CPU will panic if a prime number is encountered.

A suggestion to solve this problem is to multiply all numbers by two in your the code, and ask the user to divide them by two when they are output.

##### Macro Syntax and Evaluation Engine
The old C-style macro syntax has been replaced with a Perl-compatible regular expression system. PCRE is well known to be turing-complete, so you should have no trouble porting your macros. However, due to the Halting Problem, it
is impossible for the automatic converter tool to do this.

### Encoding
the files are encoded using Windows Code Page 932 by default for backwards-compatibility reasons, although this can be changed using the `-use-a-different-code-page=Unicode::utf-8` command-line argument to the
interpreter.

### File extension
The official file extension for the is `.`, for example `hello.`. Apparently some new users find this confusing, when really it is quite simple: in Objective C you would call your file `foo.m`, and in the you would call it `foo.`.

### Platform Support
It is impractical to support all the diverse platforms available in this day and age; therefore the will run only on [Linux on the PlayStation 2](https://www.youtube.com/watch?v=ZnXpzczPc38).

For convenience, you can emulate it on Linux using [this ROM](https://foaas.com/jinglebells/pxeger) for DosBox, on Windows using the Windows Subsystem for PlayStation 2 (enable it in `Control Panel` -> `Programs and Features` ->
`Turn Windows features on or off`), or on Macintosh OS 9 using the for Macintosh® ([download here](https://foaas.com/jinglebells/pxeger)), which is, under the hood, a Windows Virtual Machine running on top of
[Parallels](https://www.parallels.com).

### Name
The official name for the is the. However, for SEO reasons, you may also see the called thelang or theasintheprogramminglanguagenottheword (`"the", as in the programming language, not the word`).

For legal reasons, the must be spelt with a lowercase t, like the not The.

the is a registerd trademark of theasintheprogramminglanguagenottheword & Sons Co., LTD., a Delaware registered 501(c)(3) non-profit organisation.

### Contributing
1. Make sure you have signed the The Contributor's Licence Agreement Contract Terms and Conditions Policy Document
2. Read the Code of Conduct
823. Ensure your code follows the the [Style Guide](#style-guide)
3. Create a Pull Request

### Style Guide

- the code should be written with 16 spaces for indentation.
- variable names should be written in `sPOnGeBoB cAsE`, with the first letter being upper-case for variables and functions, or lower-case for classes, modules, and constants.
- macros should avoid using letters unless necessary.

