
[Back to main](index)

## Upgrade:

### Homebrew

```ruby
brew upgrade warrensbox/tap/appinstall
```
### Linux

Rerun:

```sh
curl -L https://raw.githubusercontent.com/warrensbox/github-appinstaller/release/install.sh | bash
```

## Uninstall:

### Homebrew

```ruby
brew uninstall warrensbox/tap/appinstall
```
### Linux

Rerun:

```sh
rm /usr/local/bin/appinstall
```

## Troubleshoot:

Common issues:
```ruby
install: can't change permissions of /usr/local/bin: Operation not permitted
```

```ruby
"Unable to remove symlink. You must have SUDO privileges"
```

```ruby
"Unable to create symlink. You must have SUDO privileges"
```
You probably need to have **sudo** privileges to install *appinstall*.

[Back to top](#upgrade)    
[Back to main](index)