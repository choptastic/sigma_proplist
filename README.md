# Abstraction Layer for Erlang DS

[Erlang DS](https://github.com/choptastic/erlang_ds) used to be called "Sigma
Proplist" exporting the module `pl`.  Since reworking to `ds`, this will serve
as a backwards compatibility layer for any projects depending on it.

If you are already using `sigma_proplist` in your projects, you shouldn't need
to make any changes to your rebar.config.

If you're starting a new project, just use [Erlang
DS](https://github.com/choptastic/erlang_ds) instead.

## The only thing you need to do

The only thing you'll want to do here is start `sigma_proplist` with
`application:start(sigma_proplist)`.

## About

Author: [Jesse Gumm](http://github.com/choptastic)

MIT License
