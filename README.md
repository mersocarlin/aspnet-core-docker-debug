
# aspnet-core-docker-debug

This is a sample project which shows how to debug an asp.net core project inside a Docker container on a Mac.

This source code is part of my tutorial "Debugging .NET Core inside Docker container on a Mac — The missing tutorial" posted [here](https://medium.com/@mersocarlin/debugging-net-core-inside-docker-container-on-a-mac-the-missing-tutorial-e85d7711dac9)

## Prerequisites

* [Node.js](https://nodejs.org/en/)
* [Yo generator](http://yeoman.io/)
* [Visual Studio Code](https://code.visualstudio.com/)

## Useful generators

* [generator-aspnet](https://www.npmjs.com/package/generator-aspnet): creates the web.api project
* [generator-docker](https://github.com/Microsoft/generator-docker): creates docker-compose and Dockerfiles for debug

## Debugging your project

1. `dotnet restore`
2. `./dockerTask.sh build`
3. `./dockerTask.sh composeForDebug`
4. Set a breakpoint in your code
5. [F5] and start debugging

## License

MIT
