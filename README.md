Git Repo
========

Clones a Git code repository

Requirements
------------

- Git (available via role ryanlelek.packages)

Role Variables
--------------

- **git_repo_name**: gitrepo
- **git_repo_url**: false
- **git_repo_ssh_private_key**: false
- **git_repo_ssh_public_key**: false

Dependencies
------------

Optional:  
- ryanlelek.packages

Example Playbook
----------------

    - hosts: all
      roles:
        - ryanlelek.packages
        - role: ryanlelek.git-repo
          git_repo_name: raneto
          git_repo_url: https://github.com/gilbitron/Raneto.git

License
-------

MIT

Author Information
------------------

Created by [Ryan Lelek](https://www.ryanlelek.com)  
Part of [AnsibleTutorials.com](http://www.ansibletutorials.com)
