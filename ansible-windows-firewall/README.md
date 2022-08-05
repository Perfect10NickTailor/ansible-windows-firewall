Role Name
=========

Sets Windows Firewall settings windows serversr

Requirements
------------

Configuration follows [Best practices for configuring Windows Defender Firewall](https://docs.microsoft.com/en-us/windows/security/threat-protection/windows-firewall/best-practices-configuring)

Role Defaults
--------------

| Name | Description |
| ---- | ----------- |
| win_fw_prefix | Prefix for naming created rule |
| win_fw_ports_allow_in_public | Inbound ports allowed in the public profile |
| win_fw_web_ports | ports allowed for web servers |
| win_fw_program_allowed_web_out_public | Program acces allowed outbound in public profile |

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
