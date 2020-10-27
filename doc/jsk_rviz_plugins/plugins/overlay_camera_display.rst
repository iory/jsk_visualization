OverlayCameraDisplay
====================

What is this?
-------------

OverlayCameraDisplay plugin can visualize ``sensor_msgs/Image`` on rviz as HUD overlay.
This is an improved version of [`rviz/Camera`](http://wiki.ros.org/rviz/DisplayTypes/Camera).


.. image:: images/rviz-scene-publisher.gif


Publishing Topic
----------------

* ``/rviz/overlay_camera/image`` (``sensor_msgs/Image``)

  Publish overlay image. You can change the topic name by changing ``publish_topic_name`` in Displays.
  This topic is not published by default.
  If you want to publish it, please select a ``publish image`` check box.

.. image:: images/rviz-scene-publisher.png
