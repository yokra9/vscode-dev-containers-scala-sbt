# VS Code development container definition for Scala / sbt

<table style="width: 100%; border-style: none;"><tr>
<td style="width: 140px; text-align: center;"><a href="https://aka.ms/vscode-remote/download/extension"><img width="128px" src="https://microsoft.github.io/vscode-remote-release/images/remote-extensionpack.png" alt="Visual Studio Code logo"/></a></td>
<td>
<strong>Visual Studio Code Remote Development and GitHub Codespaces</strong><br />
<i>Open your code in the cloud, in a local container, on a remote machine, or in WSL and take advantage of VS Code's full feature set.
</td>
</tr></table>

This difinition files based on [Official definition for Java development](https://github.com/microsoft/vscode-dev-containers/tree/main/containers/java).

## directories

* `.devcontainer`
  * dev container definition for Scala / sbt
* `sample`
  * sample sbt project

## Dockerfile

Dockerfile based on [Official Dockerfile for Java development](https://github.com/microsoft/vscode-dev-containers/blob/main/containers/java/.devcontainer/Dockerfile).

differencce:

* installed sbt from `scala-sbt` repository
* if you don't want to install sbt, set `INSTALL_SBT` to false at `devcontainer.json`.

## extensions installed into the container

* Scala (Metals) ( `scalameta.metals` )
  * Scala language server with rich IDE features
* Java Extension Pack ( `vscjava.vscode-java-pack` )
  * Popular extensions for Java development and more.

## License

Licensed under the MIT License. See [LICENSE](./LICENSE).
