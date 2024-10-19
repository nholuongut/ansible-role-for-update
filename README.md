# Ansible Role - update

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

## Requirements

None

## Role Variables

NA

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
    - nho.luong
```

## Hacking

There is an included Vagrant setup for hacking on this module, but IP needs to be set.

```bash
cd tests
source .hack.sh
vagrant up
ansible-playbook test.yml
...
vagrant destroy
vagrant up
ansible-playbook test.yml -vvvv
...
```

## Linting

```bash
yamllint -c yamllint.yaml .
ansible-lint .
```

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟
