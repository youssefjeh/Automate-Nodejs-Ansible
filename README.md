
# Automate Node.js Application Deployment with Ansible
This is a basic Ansible project that automates the deployment of a Node.js application




The project has two branches: `main` and `variables` . The main branch contains the basic playbook without any variables. The variables branch, on the other hand, contains an updated playbook that uses variables to make the playbook more flexible.

To get started with this project, you'll need to have `Ansible` installed on your system. 

Once you have Ansible installed, you can run the playbook with the following command:






```bash
  ansible-playbook -i hosts deploy-node.yml
```

If you want to use the variables branch, you can switch to that branch with the following command:
```bash
  git checkout variables 
```
Make sure to update the variables in the `ansible-vars.yml`  file to match your specific deployment environment.



For more information on how to use Ansible for automating your infrastructure, check out [the official Ansible documentation](https://docs.ansible.com/ansible/latest/index.html)


