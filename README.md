# cookiecutter-salt-formula
A cookiecutter to set up a salt formula with a vagrantfile for automated testing.

Creates a directory structure and a Vagrant file that will automatically provision a VM using a masterless salt-minion.

It supports Debian and Rocky (and can be easily extend to more distros).


### Create the folder structure for a salt formula using this cookiecutter
```
cookiecutter https://github.com/danielpodwysocki/cookiecutter-salt-formula.git
```

### Bring up a Rocky Linux box and apply the state to it

```
vagrant up rocky
```
### Bring up a Debian box and apply the salt state to it

```
vagrant up debian
```

### Bring up all the VMs in the Vagrantfile

```
vagrant up
```

### SSH into the rocky box
```
vagrant ssh rocky
```

### SSH into the debian box
```
vagrant ssh rocky
```
