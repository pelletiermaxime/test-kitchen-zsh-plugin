# kitchen-zsh-plugin

`kitchen-zsh-plugin` is a zsh plugin for
[Test Kitchen](http://kitchen.ci/). This plugin can be installed into oh-my-zsh [custom plugin](https://github.com/robbyrussell/oh-my-zsh#customization) folder.

## Installation for oh-my-zsh

1. In the command line, change to `oh-my-zsh` plugins directory:

    ```console
    $ take ~/.oh-my-zsh/custom/plugins
    ```

2. Clone the repository into a new directory called `kitchen`:

    ```console
    git clone https://github.com/pelletiermaxime/test-kitchen-zsh-plugin.git kitchen
    ```

3. Include `kitchen` plugin to your .zshrc file along with other plugins

4. Restart your terminal application.

## TODO

* Add driver subcommands.

## Additional information

* This is heavily based on the [vagrant zsh plugin](https://github.com/robbyrussell/oh-my-zsh/blob/master/plugins/vagrant/_vagrant)
* Caching code inspired by the [supervisor zsh plugin](https://github.com/robbyrussell/oh-my-zsh/blob/master/plugins/supervisor/_supervisorctl)
* This readme is based on the [berkshelf-zsh readme](https://github.com/berkshelf/berkshelf-zsh-plugin/blob/master/README.md)