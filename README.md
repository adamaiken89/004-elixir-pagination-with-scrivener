003-deploying-to-heroku (Sept 2021)
### Reference
https://elixircasts.io/deploying-elixir-with-heroku
### Using
  * Erlang 24.0
  * Elixir 1.12.3  
  * NodeJS 14
  * Pheonix 1.5.12

### What I learnt

  1. `mix phx.gen.schema Comment comments body:text post_id:references:posts` to create a schema
  2. All `controllers` in Phoenix are in `singular` while that in rails are usually in plurals.
  3. Have to define your own `Context`, here is `Blogs` for data manipulations
  4. Rely on module `Blogs` to do the handlers
 # 003-deploying-to-heroku
