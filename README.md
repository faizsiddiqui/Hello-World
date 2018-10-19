# Hello, World!

Language comparison!

#### Bash

`docker run --rm -v "$PWD/Bash/hello-world.sh":/hello-world.sh centos:7 bash /hello-world.sh`

#### C

`docker run --rm -v "$PWD/C/hello-world.c":/hello-world.c gcc:8 sh -c "gcc -o hello-world /hello-world.c;./hello-world"`

#### C++

`docker run --rm -v "$PWD/C++/hello-world.cpp":/hello-world.cpp gcc:8 sh -c "g++ -o hello-world /hello-world.cpp;./hello-world"`

#### Erlang

`docker run --rm -v "$PWD/Erlang/helloworld.erl":/helloworld.erl erlang:21-slim escript /helloworld.erl`

#### GoLang

`docker run --rm -v "$PWD/GoLang/hello-world.go":/hello-world.go golang:1-alpine go run /hello-world.go`

#### Haskell

`docker run --rm -v "$PWD/Haskell/hello-world.hs":/hello-world.hs haskell:8.4 sh -c "ghc -o hello-world /hello-world.hs;./hello-world"`

#### Java

`docker run --rm -v "$PWD/Java/HelloWorld.java":/HelloWorld.java java:8-alpine sh -c "javac /HelloWorld.java;java HelloWorld"`

#### NodeJS

`docker run --rm -v "$PWD/NodeJS/hello-world.js":/hello-world.js node:10-alpine node /hello-world.js`

#### Perl

`docker run --rm -v "$PWD/Perl/hello-world.pl":/hello-world.pl perl:5-slim perl /hello-world.pl`

##### PHP

`docker run --rm -v "$PWD/PHP/hello-world.php":/hello-world.php php:7.2-alpine php /hello-world.php`

##### Python

`docker run --rm -v "$PWD/Python/hello-world.py":/hello-world.py python:3-alpine python /hello-world.py`

#### Ruby

`docker run --rm -v "$PWD/Ruby/hello-world.rb":/hello-world.rb ruby:2.5.3-alpine ruby /hello-world.rb`

#### Swift

`docker run --rm -v "$PWD/Swift/hello-world.swift":/hello-world.swift swift:4 swift /hello-world.swift`
