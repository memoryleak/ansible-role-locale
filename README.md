memoryleak.locale
=================

Set the /etc/locale.conf values.

Requirements
------------

None

Role Variables
--------------
	locale_default: en_US.UTF-8
	locale_lang: {{locale_default}}
	locale_language: {{locale_default}}
	locale_lc_address: {{locale_default}}
	locale_lc_collate: {{locale_default}}
	locale_lc_ctype: {{locale_default}}
	locale_lc_identification: {{locale_default}}
	locale_lc_measurement: {{locale_default}}
	locale_lc_messages: {{locale_default}}
	locale_lc_monetary: {{locale_default}}
	locale_lc_name: {{locale_default}}
	locale_lc_numeric: {{locale_default}}
	locale_lc_paper: {{locale_default}}
	locale_lc_telephone: {{locale_default}}
	locale_lc_time: {{locale_default}}

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: memoryleak.locale }

License
-------

BSD

Author Information
------------------

Haydar Ciftci <haydar.ciftci@gmail.com>
