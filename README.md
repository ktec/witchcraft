# Witchcraft
![](./witchcraft-logo.png)

| Build Status | Documentation |
|--------------|------|
| [![Circle CI](https://circleci.com/gh/robot-overlord/witchcraft/tree/master.svg?style=svg)](https://circleci.com/gh/robot-overlord/witchcraft/tree/master) | [http://www.robotoverlord.io/witchcraft](http://www.robotoverlord.io/witchcraft/extra-readme.html) |

A monoid, functor, applicative, monad, and arrow library

*This is currently very Haskell-flavoured*. It will become more idiomatic after the first pass.

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add witchcraft to your list of dependencies in `mix.exs`:

        def deps do
          [{:witchcraft, "~> 0.2.0"}]
        end

  2. Ensure witchcraft is started before your application:

        def application do
          [applications: [:witchcraft]]
        end
