run the demo app
python3 demo_app.py

check the health - demo app should return 200 OK status

call the /down endpoint

run the rulebook
ansible-rulebook --rulebook rulebook.yml -i inventory.yml -S .

Saved search in Splunk sends event to rulebook using webhook

Rulebook evaluates condition and runs Ansible playbook to restart the demo app
