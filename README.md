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
| jenkins_listen_address		| ''								|		|
| jenkins_ajp_port			| 8009								|		|
| jenkins_ajp_listen_address		| ''								|		|
| jenkins_debug_level			| 5								|		|

Dependencies
------------

TODO

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: correcthorse.jenkins }

License
-------

MIT

Author Information
------------------

* [Joshua Rusch](https://correct.horse/)