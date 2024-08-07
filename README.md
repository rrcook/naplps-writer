# Weather Overlay

**Prodigy-style weather map in NAPLPS**

An Elixir application that will write a "weather overlay" that changes daily over
a map of the continental United States. 
The application produces a NAPLPS graphics file used in Prodigy, overlaid on top 
of a separate NAPLPS graphic.

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `naplps_writer` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:weather_overlay, "~> 0.1.0"}
  ]
end
```

A tempoary repository to develop a Prodigy-style weather map overlay using NAPLPS.
Weather will be read in from a site or API and converted to NAPLPS that will fit
on the Prodigy weather map page.

When development is completed this project will be put into [Prodigy Reloaded](https://github.com/prodigyreloaded)
