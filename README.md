correcthorse.jenkins
=========

A role for installing jenkins.

Role Variables
--------------

| Variable                              | Default							| Notes		|
| :---                                  | :---                          				| :---		|
| jenkins_stable_repo			| true								| 		|
| jenkins_java_options			| '-Djava.awt.headless=true -Djava.net.preferIPv4Stack=true'	|		|
| jenkins_port				| 8080			    					|		|
| jenkins_open_port			| false								|		|
| jenkins_listen_address		| ''								|		|
| jenkins_ajp_port			| 8009								|		|
| jenkins_open_ajp_port			| false								|		|
| jenkins_ajp_listen_address		| ''								|		|
| jenkins_debug_level			| 5								|		|

Dependencies
------------

- correcthorse.common

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: correcthorse.jenkins }

License
-------

MIT

Author Information
------------------

* [Joshua Rusch](https://correct.horse/)
