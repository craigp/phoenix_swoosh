# Phoenix.Swoosh

Use Swoosh to easily send emails in your Phoenix project.

This module provides the ability to set the HTML and/or text body of an email by rendering templates.

See the [docs](http://hexdocs.pm/phoenix_swoosh) for more information.

## Installation

Add phoenix_swoosh to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [{:phoenix_swoosh, "~> 0.3"}]
end
```

## Documentation

Documentation is written into the library, you will find it in the source code, accessible from `iex` and of course, it
all gets published to [hexdocs](http://hexdocs.pm/phoenix_swoosh).

## Contributing

### Running tests

Clone the repo and fetch its dependencies:

```
$ git clone https://github.com/swoosh/phoenix_swoosh.git
$ cd phoenix_swoosh
$ mix deps.get
$ mix test
```

### Building docs

```
$ MIX_ENV=docs mix docs
```

## LICENSE

See [LICENSE](https://github.com/swoosh/phoenix_swoosh/blob/main/LICENSE.txt)
