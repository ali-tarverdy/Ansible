### Using of ansible playbook in host ###

```bash
ansible-playbook -i server.ini --become --become-method=sudo servers/tasks/main.yaml
```
