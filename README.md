# vscode-elixir-sql-sigil

This extension allows you to get SQL syntax highlighting in Elixir via a `~Q` sigil.

```Elixir
defmodule SQL.Sigil do
  def sigil_Q(string, []), do: string
end
```

## Features

- SQL highlighting inside Elixir
