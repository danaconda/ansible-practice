# ansible-practice

This is my ansible practice. I did it by listening some udemy lections. 
It is lika a summary of all lections.

## dependencies

For use playbooks you will need ansible and at least two nodes. 
And edit inventory file. Just change ip addressess.
For run playbooks in most cases enough type command:
    
    ansible-playbook <yml-file>

## covered topics
1. **Ad-Hoc commands.** Move variables from inventory file to group_vars
2. **Simple yaml file.** Write first simple dummy yaml files.
  - ping.yml
  - install_web.yml
3. **Working with variables.** register, set_fact, debug, curly brackets.
  - variables.yml
4. **Blocks and condition.** when, block, notify, handlers.
  - simple_deploy.yml
5. **Loops.** loop, with_items, until, with_fileglob.
  - loops_playbook.yml
  - loop_deploy.yml
6. **Templates.** j2 files, template.
  - template_deploy.yml
7. **Roles.** ansible-galaxy init.
  - role_deploy.yml
8. **Include/Import playbook-files.** include.
  - include_playbook.yml
    - create_file.yml
    - create_folders.yml
9. **Delegate execution of playbook.** delegate_to, wait_for.
  - delegate_playbook.yml
10. **Errors handling.** ignore_errors, failed_when, any_errors_fatal.
  - errrorhandling_playbook.yml
11. **ansible-vault.** create, view, edit, decrypt, encrypt, encrypt_string.
  - vault_playbook.yml
