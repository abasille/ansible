# Install ansible

## Ubuntu

```
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible
```

## MacOS

Pre-requis : Homebrew installé (https://docs.brew.sh/Installation)

```
brew install ansible
```

Execute config
---

`ansible-pull -U git@github.com:abasille/ansible.git`
