<h5 align="center">
  <img src="https://elixir-lang.org/images/logo/logo.png" width="150px" /><br>
  <b>Control restaurants' supplies about to due</b> 🥓
</h5>
<p align="center">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-purple">
</p>

## :open_book: About 
This project is a simple API to control restaurants' supplies that are about to due in the current week and send email to the restaurants' responsible with the list of supplies. <br />

## :rosette: API Routes
```
GET - api/supplies/{id} - Get a supply
GET - api/supplies - Get all supplies
POST - api/restaurants - Create a restaurant
POST - api/supplies - Create a supply
```

## :bricks: This project was built with: 
- [Elixir](https://elixir-lang.org/)
- [Phoenix](https://www.phoenixframework.org/)
- [Ecto](https://hexdocs.pm/ecto/Ecto.html)
- [Bamboo](https://github.com/thoughtbot/bamboo)
- [Postgres](https://www.postgresql.org/)
- [Ecto](https://hexdocs.pm/ecto/Ecto.html)

## :running_man: Installing and Running  
 1. Clone this repository ```bash git clone https://github.com/pferreirafabricio/inmana.git```;
 2. Enter in the project's folder: ```bash cd inmana```
 3. Install all project's dependencies: ```bash mix deps.get```
 4. Create and migrate your database with ```bash mix ecto.setup```
 5. Start Phoenix endpoint with ```bash mix phx.server```
 6. Finally you can visit [`localhost:4000`](http://localhost:4000) from your browser 😃
 
## :recycle: Contribute
 1. Fork this repository;
 2. Create a branch with your feature: ```git checkout -b my-feature```
 3. Commit your changes: ```git commit -m 'feat: My new feature'```
 4. Push your branch: ```git push origin my-feature```
 
## :page_with_curl:	License
This project is under the MIT license. Take a look at the [LICENSE](LICENSE.md) file for more details.

## Learn more

  * Official website: https://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Forum: https://elixirforum.com/c/phoenix-forum
  * Source: https://github.com/phoenixframework/phoenix
