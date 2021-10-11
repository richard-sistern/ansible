# Ansible snippets

## Add a pause

```ansible
- name: Pause for something
  pause:
    seconds: 30
```

## When

****
```ansible
when: "'bla' not in ansible_hostname"
```
