# Prerequisites

Deals with the following topics:

- Package manager: [chocolatey](https://chocolatey.org/install)
- Installing and setup of software: [git](https://chocolatey.org/packages/git)
- Creating a github account: [github](https://github.com/join)

---
<!-- .slide: class="left" -->
## Packagemanager [chocolatey](https://chocolatey.org)

This is for Windows only! For Linux just use on-board-tools ;)

1. Open up an elevated Powershell console (admin).
1. Install chocolatey (see also <https://chocolatey.org/install>) by performing the following commands:

   ```bash
    Set-ExecutionPolicy Bypass -Scope Process -Force;
    iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
   ```

1. Restart elevated Powershell console and type:

   ```bash
    choco install git -y
   ```

---
<!-- .slide: class="left" -->
### You don't want to use a commandline for git?

Install a GUI:

  ```bash
   choco install github-desktop -y
  ```

### You don't want to use chocolatey? 

### Are you really sure?

Ok, then install git from [git-scm](https://git-scm.com/download/win).

---
<!-- .slide: class="left" -->
### Mini Cheat-Sheet for chocolatey

- `choco list <packagename>` ... search for a given package
- `choco list -lo` ... list local installed packages
- `choco list -li` ... list local installed managed and unmanaged packages
- `choco outdated` ... list local installed upgradeable packages
- `choco install <packagename> -y` ... install package and answer with yes during installation
- `choco uninstall <packagename>`  ... I think you know what that does, or?

For all available packages see <https://chocolatey.org/packages>.

---
<!-- .slide: class="left" -->
### Setup of git

> Beware! *Only the bare minimum is told here!*

For in-depth information see [Getting-Started](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup).

1. Open a command line - for example the newly available `git-bash`
1. type in the following two commands:

```bash
$ git config --global user.name "<YourName>"
$ git config --global user.email <YourEMail>
```

---
<!-- .slide: class="left" -->
### Github Account

Follow this link: <https://github.com/join> and ... **JOIN!**

#### Username-Recommendations

- Litec staff: `litec-<UPIS Shortcut>`
- Rest of the world: completely up to you!
