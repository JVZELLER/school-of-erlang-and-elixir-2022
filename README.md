# School of Erlang and Elixir 2022
My solutions to the exercises of the School of Erlang and Elixir 2022 spring edition.

You can find the offical repository here: https://github.com/aleklisi/SchoolOfErlangAndElixir2022

## How to start?

The solutions are stored in `.livemd` format to be runned using [Livebook](https://livebook.dev/) (check the official page for more informations)

### fly.io
You can launch `livebook` instance using https://fly.io/launch/livebook and following instructions on the website.

### docker
Alternately you can run `livebook` instance in a docker container on your local machine:

```bash
docker run -p 8080:8080 -p 8081:8081 --pull always -v $(pwd):/data livebook/livebook
```

or following the instructions from: https://github.com/livebook-dev/livebook#docker
