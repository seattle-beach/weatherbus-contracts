# weatherbus-contracts
Golden Gardens contracts for the weatherbus suite of services

## Getting started

1. Clone `https://github.com/pivotal/golden-gardens.git`, `https://github.com/seattle-beach/weatherbus.git`, `https://github.com/seattle-beach/weatherbus-bus.git`, `https://github.com/seattle-beach/weatherbus-weather.git`, `https://github.com/seattle-beach/weatherbus-web.git`, and  `https://github.com/seattle-beach/go-weatherbus-bus.git` as siblings of this repo.
2. `bundle install`
3. Orchestrate a set of tests: `bundle exec golden-gardens orchestrate perspectives/prime/orchestrator.json` (or `bus`, `go-bus`, `weather`, or `web` in place of `prime`).
