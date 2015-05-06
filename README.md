hdfs-namenode Cookbook
======================
COnfigures a node to run hdfs-datanode service

Requirements
------------

Attributes
----------

Usage
-----
#### hdfs-namenode::default
knife bootstrap IP -j '{"masterip": "x.x.x.x"}' -x vagrant -P vagrant -r 'recipe[hdfs-datanode]' --sudo

A hadoop data node will be started on IP.

Contributing
------------

License and Authors
-------------------
