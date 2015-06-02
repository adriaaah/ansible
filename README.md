# Ansible
My Ansible playbooks, which are useful to run my daily job and hope become also to you.

## Description
* Just a place where I put my own Ansible playbooks.
* They are written for Ubuntu 14 boxes.
* These playbooks are in a very early stage, so please be patient and let me improve them.
* Some files aren't uploaded due to security/privacy reasons ([.gitignore](.gitignore) rules). Anyway, I hope this code is pretty clear enough, although ...
* ... I'm starting to use Ansible Vault.

## Let's fly!
* Type something like `ansible-playbook -i production site.yml -K --ask-vault-pass`.

## To Do
* Add conditional statements in order to provide more compatibility.
* Add *useful* features to Apache and MySQL playbooks.

## Disclaimer
* Read [LICENSE](LICENSE) file.
* Although all this content is public and free (read [LICENSE](LICENSE) file), it was designed for the servers I manage, so you **should** modify it.
* Suggestions and improvements are welcome. Otherwise, crap content goes to `/dev/null`.

## Bonus
* A basic [Kickstart file for Ubuntu](kickstart-ubuntu-template.ks) created with `system-config-kickstart` Ubuntu tool. Yes, I should move to another place. Maybe someday, you know.
