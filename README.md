# ruby_cli_devcontainer

I've created a container for developing in Ruby. To ensure a unified development environment, I'm using Remote Containers. Here's what you need:

- **IDE**
  - Visual Studio Code (VSCode)
- **Extensions**
  - Remote Development
- **Tools**
  - Docker

Additional Information:
- Ensure that Docker is installed and running on your machine. Docker will be used to create and manage your development container.
- Install the "Remote Development" extension pack in VSCode. This pack includes "Remote - Containers", "Remote - SSH", and "Remote - WSL" extensions, allowing you to develop inside containers, remote machines, or Windows Subsystem for Linux (WSL) seamlessly.
- Configure your `devcontainer.json` file in your project to specify the container configuration, such as the Dockerfile path, ports to forward, and any extensions you want installed in the container environment.
- After setting up, you can open your project in VSCode and use the "Remote-Containers: Open Folder in Container..." command to start developing inside the container. This approach guarantees that everyone on your team works with the same development environment, avoiding the "it works on my machine" problem.

This setup provides a robust environment for Ruby development, leveraging the power of Docker and the flexibility of VSCode to create a consistent and efficient workflow for you and your team.