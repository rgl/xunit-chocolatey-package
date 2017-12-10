[xunit.runner.console](https://www.nuget.org/packages/xunit.runner.console) nuget package re-packaged as a chocolatey package.

Run `package.ps1` to create the chocolatey package inside the `tmp/pkg` directory.

Run `choco install -y xunit -Source tmp/pkg` to install locally.
