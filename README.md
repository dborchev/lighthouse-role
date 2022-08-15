Role Name
=========

Этот плейбук скачивает и устанавливает на целевые хосты группы [LightHouse](https://github.com/VKCOM/lighthouse)
* LightHouse всегда последней версии из репозитория, обслуживается nginx последней версии доступной в EPEL

Requirements
------------

Требуется хоть какой-то веб-сервер, например [nginx](https://galaxy.ansible.com/nginxinc/nginx_core)/
Эта роль только скачивает lighthouse в `{{ document_root }}/lighthouse-master`.


Role Variables
--------------

* используя `document_root` можно указать альтернативный путь распаковки LightHouse

Dependencies
------------



Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: dborchev.lighthouse-role

License
-------

BSD

Author Information
------------------
N/A