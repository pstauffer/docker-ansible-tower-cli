# docker-ansible-tower-cli

## Description
This is a docker image for the command line tool **tower-cli** for Ansible Tower. [More Informations](http://tower-cli.readthedocs.io).

## Usage

```
# one shot
docker run --rm -v /root/.tower_cli.cfg:/home/cli/.tower_cli.cfg:ro -it pstauffer/ansible-tower-cli <options>

# with an alias
alias tower-cli=“docker run --rm -v /root/.tower_cli.cfg:/home/cli/.tower_cli.cfg:ro -it pstauffer/ansible-tower-cli”
tower-cli host list
```

## License
This project is licensed under [MIT](http://opensource.org/licenses/MIT).
