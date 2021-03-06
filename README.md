# MIND Mobility Custom Component (for Home Assistant)

This component if for cars that have a module from [Mind Mobility](https://mindmobility.nl/) like the cars (Volkswagen, Seat, Audi, Skoda) from importer PON in the Netherlands.

It gives you the location of the car, status (locks, ignition, parking brake) and some metrics (fuel, mileage).

## Configuration:

```yaml
mind:
  username: your@email.com
  password: YoUrPaSsWoRd
```

You might need to specify a `client_id` and `client_secret` if you get a login failed message. You will have to find the right values yourself if the values here don't work.

```yaml
mind:
  username: your@email.com
  password: YoUrPaSsWoRd
  # Skoda:
  client_id: c030ad63a0e4433d86e4a36fc4047ce2
  client_secret: E97F8294804c49Cd83b0b9f0552577B2
  # Seat:
  client_id: 8ba04cb3869f4b568ea54fc57154d957
  client_secret: b7fD6c394a7c4aFd998afA70Cb5fED86
```