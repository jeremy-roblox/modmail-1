# ModMail

[![Discord](https://discord.com/api/guilds/576016832956334080/widget.png)][discord]
[![License](https://img.shields.io/github/license/chamburr/modmail.svg)](LICENSE)

A feature-rich Discord bot for easy communication between server staff and users.

![Screenshot](https://chamburr.xyz/u/7PUf0Z.png)

A new channel is created whenever a user messages the bot, and the channel will serve as a shared
inbox for seamless communication between staff and the user.

To learn more, check out our [website](https://modmail.xyz) or visit our [Discord server][discord].

## Contributing

There are many ways you can contribute to this project:

- [Submitting bugs and suggestions](https://github.com/chamburr/modmail/issues)
- [Reviewing pull requests](https://github.com/chamburr/modmail/pulls)
- [Contribute directly to the code base](https://github.com/chamburr/modmail/pulls)

For more information, please see our [contributing guidelines](CONTRIBUTING.md).

The issue tracker here is only for bug reports and suggestions. Please do not use it to ask a
question. Instead, ask it on our [Discord server][discord].

## Self-hosting

This guide requires you to have basic knowledge about command line, Docker and Discord bots. We
will not provide any form of support for self-hosting.

First, create a Discord bot on the [developer portal](https://discord.com/developers). You must
enable the server member intent and the message content intent for the bot to function.

Then, install Git and Docker on your machine. Clone this repository, copy `docker/.env.example` to
`docker/.env` and fill in all the configurations.

Finally, run the following commands to build and run ModMail. Please note that the initial build
may take 10 to 15 minutes, depending on your machine. Subsequent builds would be much faster.

```
cd docker
docker-compose up -d
```

Your self-hosted bot should be up now. Congratulations!

## License

This project is licensed under [GNU Affero General Public License v3.0](LICENSE).

[discord]: https://discord.gg/wjWJwJB
