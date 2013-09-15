boto v2.xx.x
============

:date: 2013/xx/xx

This release adds ____.


Features
--------

* . (:issue:``, :sha:``)


Bugfixes
--------

* Fixed test fallout from the EC2 dry-run change. (:sha:`2159456`)
* Added tests for more of SWF's ``layer2``. (:issue:`1718`, :sha:`35fb741`,
  :sha:`a84d401`, :sha:`1cf1641`, :sha:`a36429c`)
* Changed EC2 to allow ``name`` to be optional in calls to ``copy_image``.
  (:issue:`1672`, :sha:` 26285aa`)
* Added ``billingProducts`` support to EC2 ``Image``. (:issue:`1703`,
  :sha:`cccadaf`, :sha:`3914e91`)
* Fixed a place where ``dry_run`` was handled in EC2. (:issue:`1722`,
  :sha:`0a52c82`)
* Fixed ``run_instances`` with a block device mapping. (:issue:`1723`,
  :sha:`974743f`, :sha:`9049f05`, :sha:`d7edafc`)
* Several documentation improvements/fixes:

    * Added the "Apps Built On Boto" doc. (:sha:`3bd628c`)
