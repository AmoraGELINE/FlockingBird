# Roost

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)
[![Maintainability](https://api.codeclimate.com/v1/badges/d27492e9817263c1e9b3/maintainability)](https://codeclimate.com/github/Flockingbird/roost/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/d27492e9817263c1e9b3/test_coverage)](https://codeclimate.com/github/Flockingbird/roost/test_coverage)

Roost is the Proof of Concept server and webapp for Flockingbird.

[Flockingbird](https://flockingbird.social) is a professional social network,
where you manage your business network. Decentralised, and privacy friendly.

[Flockingbird](https://flockingbird.social)

## Get started

Ensure you have Postgres and Ruby 2.3 or higher installed, then run the setup script:

```sh
make install
```

## Using the Application

Start the web server and processors (reactors and projectors):

```sh
make run
```

## Develop

We use [envent_sourcery](https://github.com/envato/event_sourcery) by
Envato. If unsure "where something goes", just ask, or read up on event
sourcing starting at event_sourcery README.

Make sure to add tests for any feature or bugfix.

Test with
```sh
make
```

This also enforces some code style guidelines once the tests pass.
