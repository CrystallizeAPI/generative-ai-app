# Crystallize - Generate Content with AI APP

## Requirements

-   Volta.sh (that will bring good version of Node )
-   Docker
-   Node: 20.x
-   PNPM: 9+

## Installation

```bash
make install
```

> Important!: You need to adapt variables in the `application/.env`.

## Run the project

```bash
make serve
```

> you can stop non stopped services with `make stop-services`

-   Frontend: http://localhost:29080
-   Mailcatcher - Web: http://localhost:29082

## Contributing

-   `make codeclean` will keep the project in order.
-   `make tests` will run the tests.
