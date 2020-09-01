# Elixir Example

To run on Kintohub
- use the `Dockerfile` option and you are set 
- choose `elixir` from the UI and add the following commands
```
# Build command
mix local.hex --force && mix local.rebar --force && mix deps.get --quiet && mix

# run command
mix run --no-halt
```


> Note: for both options port is `3000` and subfolder path is `.`
