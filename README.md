# 004-elixir-pagination-with-scrivener (Sept 2021)
### Reference
https://elixircasts.io/elixir-pagination-with-scrivener
### Using
  * Erlang 24.0
  * Elixir 1.12.3  
  * NodeJS 14
  * Pheonix 1.5.12

### What I learnt
  https://github.com/drewolson/scrivener_ecto
  * Put the project dependencies to `deps` in `mix.exs`
  * Run `mix deps.get` to install those dependencies
  * Set `use Scrivener, page_size: 4` with default page size in `lib/teacher/repo.ex`

### Notes for the latest version of phoenix
  * No need to specify the dependenies in `application` anymore
  * `scrivener_html` does not support the latest phoenix 1.5.x version
