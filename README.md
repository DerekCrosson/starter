# Starter

A boilerplate to get new projects started quickly.

**Ruby version:** 3.3.3
**Rails version:** 7.1.3.4

## System dependencies

[Postgres 16](https://formulae.brew.sh/formula/postgresql@16)

Node v22.3.0 (it's best to use [nvm](https://medium.com/@priscillashamin/how-to-install-and-configure-nvm-on-mac-os-43e3366c75a6) to manage this)

esbuild is used to bundle the application's Javascript, configured to automatically refresh the browser as you make changes to the code.

Tailwind and postcss is used for styling.

The Hotwire stack is used for fater page loads (Turbo Drive), partial page updates (Turbo Frames), reactive page updates (Turbo Stream), and frontend interactivity (Stimulus).

CableReady and StimulusReflex allows even more server-powered frontend interactivity and reactive page updates.

Mrujs is used to replace some feature from Rails/UJS and for its powerful CableCar plugin.

Postgres is configured to use UUIDs for the primary keys.

### Database creation

```zsh
rails db:create
```

### Database migration

```zsh
rails db:migrate
```

### Database seeding

```zsh
rails db:seed
```

### Start the application

```zsh
./bin/dev
```

### Run the test suite

```zsh
rails test
```
