# Hello, World!

[![build](https://github.com/jaredsburrows/hello-world/actions/workflows/build.yml/badge.svg)](https://github.com/jaredsburrows/hello-world/actions/workflows/build.yml)

Compiling "Hello, World!" in multiple languages with Github Actions.

| Language                                                                                                                                           | Compiler      | Github Action                                                                          |
|----------------------------------------------------------------------------------------------------------------------------------------------------|---------------|----------------------------------------------------------------------------------------|
| [Assembly](https://nasm.us)                                                                                                                        | nasm          | [ilammy/setup-nasm](https://github.com/ilammy/setup-nasm)                              |
| [Awk](https://gnu.org/software/gawk/manual/gawk.html)                                                                                              | awk           | N/A (Apart of the Linux/Mac shell)                                                     |
| [Bash](https://gnu.org/software/bash)                                                                                                              | bash          | N/A (Apart of the Linux/Mac shell)                                                     |
| [Batch](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/windows-commands)                                         | batch         | N/A (Apart of the Windows command prompt)                                              |
| [C](https://open-std.org/jtc1/sc22/wg14)                                                                                                           | gcc           | [egor-tensin/setup-gcc](https://github.com/egor-tensin/setup-gcc)                      |
| [C#](https://learn.microsoft.com/en-us/dotnet/csharp)                                                                                              | dotnet        | [actions/setup-dotnet](https://github.com/actions/setup-dotnet) (Official)             |
| [C++](https://isocpp.org)                                                                                                                          | g++           | [egor-tensin/setup-gcc](https://github.com/egor-tensin/setup-gcc)                      |
| [Clojure](https://clojure.org)                                                                                                                     | clojure       | [DeLaGuardo/setup-clojure](https://github.com/DeLaGuardo/setup-clojure)                |
| [Cobol](https://gnucobol.sourceforge.io/faq/index.html)                                                                                            | cobc          | [fabasoad/setup-cobol-action](https://github.com/fabasoad/setup-cobol-action)          |
| [D](https://dlang.org)                                                                                                                             | dmd           | [dlang-community/setup-dlang](https://github.com/dlang-community/setup-dlang)          |
| [Dart](https://dart.dev)                                                                                                                           | dart          | [dart-lang/setup-dart](https://github.com/dart-lang/setup-dart) (Official)             |
| [Erlang](https://erlang.org)                                                                                                                       | erl           | [erlef/setup-beam](https://github.com/erlef/setup-beam) (Official)                     |
| [F#](https://learn.microsoft.com/en-us/dotnet/fsharp)                                                                                              | dotnet        | [actions/setup-dotnet](https://github.com/actions/setup-dotnet) (Official)             |
| [Fortran](https://erlang.org)                                                                                                                      | gfortran      | [fortran-lang/setup-fortran](https://github.com/fortran-lang/setup-fortran) (Official) |
| [Go](https://go.dev)                                                                                                                               | go            | [actions/setup-go](https://github.com/actions/setup-go) (Official)                     |
| [Groovy](https://groovy-lang.org)                                                                                                                  | groovy        | [WtfJoke/setup-groovy](https://github.com/WtfJoke/setup-groovy)                        |
| [Haskell](https://haskell.org)                                                                                                                     | ghc           | [haskell-actions/setup](https://github.com/haskell-actions/setup) (Official)           |
| [HTML](https://w3.org/html)                                                                                                                        | lynx (For CI) | N/A (Apart of the Linux/Mac shell)                                                     |
| [Java](https://java.com/en)                                                                                                                        | javac         | [actions/setup-java](https://github.com/actions/setup-java) (Official)                 |
| [JavaScript](https://developer.oracle.com/javascript)                                                                                              | node (For CI) | [actions/setup-node](https://github.com/actions/setup-node) (Official)                 |
| [Kotlin](https://kotlinlang.org)                                                                                                                   | kotlinc       | [fwilhe2/setup-kotlin](https://github.com/fwilhe2/setup-kotlin)                        |
| [Lisp](https://lisp-lang.org)                                                                                                                      | sbcl          | [cheeze2000/setup-sbcl](https://github.com/cheeze2000/setup-sbcl)                      |
| [Lua](https://lua.org)                                                                                                                             | lua           | [xpol/setup-lua](https://github.com/xpol/setup-lua)                                    |
| [Objective-C](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html) | clang         | [egor-tensin/setup-clang](https://github.com/egor-tensin/setup-clang)                  |
| [OCaml](https://ocaml.org)                                                                                                                         | ocamlopt      | [ocaml/setup-ocaml](https://github.com/ocaml/setup-ocaml) (Official)                   |
| [Pascal](https://www.freepascal.org)                                                                                                               | pascal        | [fabasoad/pascal-action](https://github.com/fabasoad/pascal-action)                    |
| [Perl](https://perl.org)                                                                                                                           | perl          | [shogo82148/actions-setup-perl](https://github.com/shogo82148/actions-setup-perl)      |
| [PHP](https://php.net)                                                                                                                             | php           | [shivammathur/setup-php](https://github.com/shivammathur/setup-php)                    |
| [PowerShell](https://learn.microsoft.com/en-us/powershell)                                                                                         | pwsh          | N/A (Apart of the Linux/Mac Shell on Github)                                           |
| [Python](https://python.org)                                                                                                                       | python        | [actions/setup-python](https://github.com/actions/setup-python) (Official)             |
| [R](https://r-project.org)                                                                                                                         | Rscript       | [r-lib/actions/setup-r](https://github.com/r-lib/actions) (Official)                   |
| [Racket](https://racket-lang.org)                                                                                                                  | racket        | [Bogdanp/setup-racket](https://github.com/Bogdanp/setup-racket)                        |
| [Ruby](https://ruby-lang.org/en)                                                                                                                   | ruby          | [ruby/setup-ruby](https://github.com/ruby/setup-ruby) (Official)                       |
| [Rust](https://rust-lang.org)                                                                                                                      | rustc         | [ATiltedTree/setup-rust](https://github.com/ATiltedTree/setup-rust) (Official)         |
| [Scala](https://scala-lang.org)                                                                                                                    | scala         | [olafurpg/setup-scala](https://github.com/olafurpg/setup-scala)                        |
| [Swift](https://swift.org)                                                                                                                         | swiftc        | [swift-actions/setup-swift](https://github.com/swift-actions/setup-swift)              |
| [TypeScript](https://typescriptlang.org)                                                                                                           | node (For CI) | [actions/setup-node](https://github.com/actions/setup-node) (Official)                 |
