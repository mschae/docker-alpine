Build Elixir on Alpine Linux
=====

Alpine Linux minimal environment for compiling Elixir.

Image size: **45.09 MB**

See [Erlang/Elixir on Alpine Linux](https://github.com/msaraiva/alpine-erlang) to learn more about creating **minimal Erlang/Elixir docker images with Alpine Linux**.

The following packages are pre-installed:

- sudo 
- git 
- make 
- erlang 
- erlang-crypto 
- erlang-syntax-tools
- erlang-inets
- erlang-ssl
- erlang-public-key
- erlang-asn1
- erlang-sasl
- erlang-erl-interface 
- erlang-dev
- erlang-parsetools
- erlang-eunit
- erlang-tools

## Usage

```
docker run --rm -it msaraiva/build-elixir

$ git clone https://github.com/elixir-lang/elixir.git
$ cd elixir
$ make

```
