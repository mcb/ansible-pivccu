# ansible-pivccu
Ansible scripts to setup RaspberryPi with [pivccu](https://github.com/alexreinert/piVCCU/)

## Setup

Run `ansible-playbook playbook.yml -i hosts --sudo` (you might want to adjust the hostname for your pi accordingly). Please make sure you do not have to login, but rather add your pub key to the authorized_keys file.

## License

See [LICENSE](LICENSE) for details.
