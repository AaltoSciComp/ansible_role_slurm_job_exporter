# ansible_role_slurm_job_exporter
Ansible role to setup slurm jobs with gpu stats reporting to prometheus


Role Variables
--------------

nvidia_install_dcgm (logical): Actual nvidia dcgm management is outside this role. But if that is installed then set this to true. Otherwise there can be a race condition for service start at boot.
gpumonitoring_enabled (logical): Wether to apply this role or not.


Dependencies
------------

Nvidia DCGM setup needs to happen outside this role.


License
-------

MIT

