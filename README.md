# Azurefire on Ansible

This is an Ansible playbook that I use to manage the server I use to stash
miscellaneous Things That Need a Host, so that I can spin it up and down easily
if I need to.

## What's Here

 * [PushBot](https://github.com/smashwilson/pushbot), a
   [Hubot](https://hubot.github.com/) that's here to protect us.

## Using

I don't really expect this to be particularly useful to anyone else, but just
in case, here's how you run it:

```bash
cp credentials.yml.example credentials.yml
${EDITOR} credentials.yml

ansible-playbook -i "${SERVER_HOSTNAME}," site.yml
```
