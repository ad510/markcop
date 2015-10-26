# Markcop [![Circle CI](https://circleci.com/gh/hackedu/markcop.svg?style=svg)](https://circleci.com/gh/hackedu/markcop)

Markcop is our friendly Markdown enforcer.

## Running It

Copy and paste the following into your terminal (must have Docker installed):

    docker run -v $(pwd):/app hackedu/markcop

If you'd rather run it directly without docker, run the following:

    curl -sL https://git.io/vswrY | bash

If you're worried about piping from the internet to bash (which you should be),
you can run Markcop manually by downloading `bin/markcop` and running it
manually.

## License

See [LICENSE](LICENSE).
