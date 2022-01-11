<h1 align="center">The Wumpy project</h1>

<p align="center">
  <a href="https://github.com/wumpyproject">
    <img src="https://img.shields.io/github/stars/wumpyproject?color=22272e&logo=github&style=flat-square" alt="Total organization stars" />
  </a>
  <a href="https://github.com/wumpyproject/wumpy">
    <img src="https://img.shields.io/github/issues/wumpyproject/wumpy?color=22272e&logo=github&style=flat-square" alt="Main repository issues" />
  </a>
  <a href="https://github.com/wumpyproject/wumpy">
    <img src="https://img.shields.io/github/issues-pr/wumpyproject/wumpy?color=22272e&logo=github&style=flat-square" alt="Main repository PRs" />
  </a>
</p>

The Wumpy project is a collection of subpackages under the `wumpy` namespace
for interacting with the Discord API.

## Usability

- Don't be frightened by the extensibility of the Wumpy project, as a newer bot
  developer the Wumpy project aims to be forgiving, easy to use, and provide a
  great editor experience.

- As a larger bot developer, use the extensibility of the Wumpy project to your
  advantage as you scale your bot to more guilds. You can for example customize
  the cache, switch out the ratelimiting system, consume events from Redis or a
  RabbitMQ queue or use any specific subpackage independently.

- The point of the Wumpy project is to provide simple, smaller, re-usable
  implementations of the Discord API. Consider building your own library off of
  Wumpy's subpackages instead of re-implementing what so many people have
  already done previously. It is usually only the highest level of abstraction
  that differs between libraries.

🙌 Wumpy is simply for everyone!

## Plans and Triaging

Take a look at the [organization project](https://github.com/orgs/wumpyproject/projects/1)
to follow the development of the Wumpy project.

## Contributing

Take a look at the specific contributing guide depending on what part of the
project you wish to contribute to. The `wumpy` is a monorepository that holds
all the core parts of the project that closely implement the Discord API, all
other repositories are other useful subpackages for different purposes.

Unlike many other projects, all Wumpy repositories accept all kinds of
contributions from smaller documentation or cosmetic changes to larger
features and changes. If you are unsure open a GitHub Issue or Discussion
about it so that we can discuss it! ❤️
