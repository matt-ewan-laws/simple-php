# Simple PHP Boilerplate

## Development

### Requirements

* [Lando](https://lando.dev/)

### Running Dev Environment

1. `$ lando start`
2. `$ ./watch`

### File Structure

```
root/
├── lib/
│   └── router.php
├── routes.php
├── views/
│   ├── partials/
│   │   ├── footer.php
│   │   ├── header.php
│   │   └── ...
│   └── home.php
└── ...
```

Set the routes in `routes.php`. [See the router docs](https://phprouter.com) for more information.

## Build

``` sh
./build.sh
```
