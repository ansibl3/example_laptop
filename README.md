Steps:

mkdir -p roles/

ansible-galaxy install -r example-requirements.yml -p roles/

sudo ansible-playbook --connection=local --sudo -vvvv run.yml


