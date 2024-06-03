# ansible-demo-box
Ansible role with ansbile-lint usage example

## Ansible lint with Github Actions

* Create repository
* Create ansible-lint.yml in the ``.github/workflows/``
* Define the events that will trigger the action: 
    ``` 
       on:
        push:
        pull_request:
   ```
