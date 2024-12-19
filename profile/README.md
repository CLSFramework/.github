# Cross Language Soccer Framework

Cross Language Soccer Framework is a project that aims to make RoboCup Soccer Simulation 2D more accessible to new teams by providing a framework that allows teams to write their code in any programming language they want.

If you want to know more about how this project works, you can read the project documentation wiki [[HERE](https://clsframework.github.io/docs/introduction/)].

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/hH-5rkhiQHg/0.jpg)](https://www.youtube.com/watch?v=hH-5rkhiQHg&t=0s)

## Project Parts
The project is divided into the following parts:

* **Project Documentation** - [`wiki`](https://clsframework.github.io/docs/introduction/)

    The project documentation.
* **Py2D Base Code** - [`py2d-base-code`](https://github.com/CLSFramework/py2d)

  Py2D base code is a powerful sample team for soccer simulation 2D league.

* **Soccer Simulation Proxy** - [`soccer-simulation-proxy`](https://github.com/CLSFramework/soccer-simulation-proxy)

    The project's main part, a proxy that allows teams to write their code in any programming language and then communicate with the soccer server using the proxy. This project is based on [[helios-base](https://github.com/helios-base/helios-base)].

* **Playmaker Server Python** - [`playmaker-server-python`](https://github.com/CLSFramework/playmaker-server-python)

    A Python agent that can be used to control the team players.

* **Sample Playmaker Server Python gRPC** - [`sample-playmaker-server-python-grpc`](https://github.com/CLSFramework/sample-playmaker-server-python-grpc)

    A sample Python agent that uses the gRPC protocol to communicate with the proxy.

* **Sample Playmaker Server Python Thrift** - [`sample-playmaker-server-python-thrift`](https://github.com/CLSFramework/sample-playmaker-server-python-thrift)

    A sample Python agent that uses the Thrift protocol to communicate with the proxy.

* **Playmaker Server Node.js** - [`playmaker-server-nodejs`](https://github.com/CLSFramework/playmaker-server-nodejs)

    A Node.js agent that can be used to control the team players.

* **Playmaker Server C#** - [`playmaker-server-csharp`](https://github.com/CLSFramework/playmaker-server-csharp)

    A C# agent that can be used to control the team players.
