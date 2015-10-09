# ansible-java

Install Oracle Java.

# Role variables

    oracle_java_version: 8
    oracle_java_state: latest
    oracle_java_default: yes

Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: olujicz.java }
