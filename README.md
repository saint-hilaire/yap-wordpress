# Lampsible

## In progress...

## Installing

* Typical pip install - from root of source tree, run: `python3 -m pip install .`
* Install needed Ansible modules with Ansible Galaxy (this is an ugly temporary workaround which will hopefully be improved soon. It does not honor your virtual environment if you have it, but installs (on my machine at least) to ~/.ansible/):
  * `ansible-galaxy collection install community.crypto`
  * `ansible-galaxy collection install community.mysql`

## Usage

For now: `lampsible --help`  

This will be improved in the future.
