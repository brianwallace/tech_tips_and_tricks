# Update ChefDK In OSx

## ChefDK

Need to upgrade ChefDK in OSX?  Use a homebrew-cask!

```
> brew update
Already up-to-date.
.
.
.
> brew cask install --force chefdk
==> Downloading https://opscode-omnibus-packages.s3.amazonaws.com/mac_os_x/10.11/x86_64/chefdk-0.12.0-1.dmg
######################################################################## 100.0%
==> Verifying checksum for Cask chefdk
==> Running installer for chefdk; your password may be necessary.
==> Package installers may write to any location; options such as --appdir are ignored.
Password:
==> installer: Package name is Chef Development Kit
==> installer: Upgrading at base path /
==> installer: The upgrade was successful.
🍺  chefdk staged at '/opt/homebrew-cask/Caskroom/chefdk/0.12.0-1' (6 files, 112M)
```


REF: http://www.ahwkong.com/post/2015/02/04/update-chefdk-in-osx/
