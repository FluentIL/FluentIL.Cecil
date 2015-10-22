# FluentIL.Cecil
Do you like emitting? Do you love Mono.Cecil? Do you need it? FluentIL.Cecil is an emitting helper library that can help you.

This is a community project, free and open source. Everyone is invited to contribute, fork, share and use the code. No money shall be charged by this software, nor it will be. Ever.

[![Nuget count](http://img.shields.io/nuget/v/fluentil.cecil.svg)](https://www.nuget.org/packages/fluentil.cecil/)
[![Nuget downloads](http://img.shields.io/nuget/dt/fluentil.cecil.svg)](https://www.nuget.org/packages/fluentil.cecil/)

If you are looking for plain .net emitting, please check [FluentIL](http://github.com/fluentil/fluentil) project.

## Installing

FluentIL.Cecil is avaiable on Nuget

````shell
Install-Package FluentIL.Cecil
````

## Getting and building the code

To build the source code:

````shell
git clone https://github.com/FluentIL/FluentIL.Cecil.git
cd FluentIL.Cecil
nuget restore
.\build.cmd
````

Be happy!

## Contributing

Questions, comments, bug reports, and pull requests are all welcome. Bug reports that include steps-to-reproduce (including code) are preferred. Even better, make them in the form of pull requests. Before you start to work on an existing issue, check if it is not assigned to anyone yet, and if it is, talk to that person.

## Pull request

If you wrote something that you would like to share, please create a pull request.

You have to do that in the command line:

````shell
# add the main repo with the `fluentil` name
git remote add fluentilcecil https://github.com/FluentIL/FluentIL.cecil.git
# checkout the master branch
git checkout master
# download the latest changes from the master repo
git pull fluentilcecil master
# go back to your working branch
git checkout <youbranchname>
# integrate your changes
git merge master
# solve integration conflicts
````

You can solve the conflicts in your favorite text editor, or, if you are using Visual Studio, you can use it as well. Visual Studio actually presents the conflict in a very nice way to solve them. Also, on the go back to your working branch step you can go back to using Visual Studio to control git, if you prefer that.

If you know git well, you can rebase your changes instead of merging them. If not, it is ok to merge them. When your changes are up to date with the master branch then you should push them to your Github repo and then you will be able to issue a pull request and mention the issue you were working on. Make your PR message clear. If when you are creating the pull request on Github it mentions that the PR cannot be merged because there are conflicts it means you forgot to integrate the master branch. Correct that push the changes to your personal repo. This will automatically update the PR. The project maintainers should not have to resolve merge conflicts, you should.

After your pull request is accepted you may delete your local branch if you want. Update your master branch so you can continue to contribute in the future. And thank you! :)

If your pull request is denied try to understand why. It is not uncommon that PRs are denied but after some discussing and fixing they are accepted. Work with the community to get it to be the best 


