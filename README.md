# Jon's Desktop

My ubuntu desktop setup.

## How to

1. Install prerequisites (git, pip, ansible):
   
    ```
    sudo apt-get install git pip3
    pip install ansible
    ```

2. Clone this repo:

    ```
    git clone git@github.com:jonpugh/desktop.git 
    ```

3. Configure as needed.

    Vars and roles are in local.yml. See each role's README for common variables like `php_version`.

4. Run Ansible Playbook.
 
    ```
    ansible-playbook local.yml
    ```

## @TODO:

- [ ] Set fish as default shell
- [ ] Set up terminal profiles.
- [ ] Add fish abbreviations.
- [ ] Clone projects like devshop.
- [ ] Create setup.yml to install crontab for automated setup and update.
- [ ] ?
