```yaml
---
- hosts: web
  tasks:
    - name: copy test.txt file
      copy:
        src: test.txt
        dest: /tmp/test.txt
```
