# LWOS
**Light Weight Operating System**  

A begginer friendly linux distribution, based on the stable foundation of Debian, with a package manager called apt-bundle. This package manager installs apt packages as standalone xec bundles.  

## Development
This is a PROTOTYPE release, not tested, was made in half an hour.
PLEASE tell what you think about this. Star this repo if you liked this and want us to continue development.

## How to test this?:
Extract the contents of the `VBOXVM.zip` file anywhere, then open VirtualBox, click on the OPEN (+) button at the top, and open the folder to which you extracted the zip, then open the `LWS 0.2.vbox` file.

> [!IMPORTANT]
> Login with the default username, `user` whose password is `pass`
> 
> The usual debian stuff is left untouched. I will never remove the `apt` package manager, as not all packages that are installed using `apt-bundle` will work.

## How to use apt-bundle:
- To install a package: `$ apt-bundle <package-name>`
- To open a package installed by apt-bundle: `$ start <package-name>`
- To remove a package: `$ rm -rf /Programs/<package-name>.xec`

## Screenshots
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/e9b6feef-fd44-4967-8d87-9a3ad0a26460" />
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/7c49ddf4-2f23-4cad-8630-ecf2e453860b" />
