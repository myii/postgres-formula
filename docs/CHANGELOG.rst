
Changelog
=========

`0.37.0 <https://github.com/myii/postgres-formula/compare/v0.36.0...v0.37.0>`_ (2019-05-02)
-----------------------------------------------------------------------------------------------

Code Refactoring
^^^^^^^^^^^^^^^^


* **kitchen:** prefer ``kitchen.yml`` to ``.kitchen.yml`` (\ `86f853a <https://github.com/myii/postgres-formula/commit/86f853a>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **gemfile:** prepare for ``inspec`` testing (\ `e14a0dc <https://github.com/myii/postgres-formula/commit/e14a0dc>`_\ )
* **kitchen:** use newly available pre-salted images (\ `a3e4f91 <https://github.com/myii/postgres-formula/commit/a3e4f91>`_\ )
* **kitchen:** use pre-salted images as used in ``template-formula`` (\ `d654f83 <https://github.com/myii/postgres-formula/commit/d654f83>`_\ )
* **pillar_from_files:** use custom pillar based on ``pillar.example`` (\ `fb94336 <https://github.com/myii/postgres-formula/commit/fb94336>`_\ )
* **travis:** add ``.travis.yml`` based on ``template-formula`` (\ `6cc4e8b <https://github.com/myii/postgres-formula/commit/6cc4e8b>`_\ )

Documentation
^^^^^^^^^^^^^


* **readme:** update ``Testing`` section for ``inspec`` (\ `e158164 <https://github.com/myii/postgres-formula/commit/e158164>`_\ )

Features
^^^^^^^^


* implement ``semantic-release`` (\ `728d560 <https://github.com/myii/postgres-formula/commit/728d560>`_\ )

Tests
^^^^^


* **inspec:** add tests for multiple ports and postgres versions (\ `c4b46b4 <https://github.com/myii/postgres-formula/commit/c4b46b4>`_\ )
* **inspec:** enable ``use_upstream_repo`` for ``debian`` & ``centos-6`` (\ `7c6fbec <https://github.com/myii/postgres-formula/commit/7c6fbec>`_\ )
* **inspec:** replace ``serverspec`` with ``inspec`` tests (\ `ede61f1 <https://github.com/myii/postgres-formula/commit/ede61f1>`_\ )
* **inspec:** use relaxed command output match for the time being (\ `6dc3aa0 <https://github.com/myii/postgres-formula/commit/6dc3aa0>`_\ )
