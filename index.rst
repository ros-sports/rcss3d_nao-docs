.. Rcss3d Nao documentation master file, created by
   sphinx-quickstart on Fri Feb  4 12:37:35 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Rcss3d Nao
==========

Rcss3d Nao is a ROS2 package that provides an interface to the RoboCup 3D Simulator SimSpark that
closely matches a Softbank Nao robot interface.

The package aims to provide an interface that closely matches that of the the physical Softbank NAO
so it can be used in the RoboCup Standard Platform League.

Publishing / Subscription is performed using interfaces specific to the Nao (`nao_command_msgs`_ and
`nao_sensor_msgs`_), such that this simulated Nao robot can be substituted out for a real robot
seamlessly.

The project is hosted on `Github`_ by ROS Sports.

.. toctree::
   :hidden:
   :maxdepth: 2

   installation
   getting-started
   topics
   parameters
   differences-with-real-robot

.. _nao_command_msgs: https://index.ros.org/p/nao_command_msgs/
.. _nao_sensor_msgs: https://index.ros.org/p/nao_sensor_msgs/
.. _Github: https://github.com/ijnek/rcss3d_nao