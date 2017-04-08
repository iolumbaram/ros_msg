# ros_msg

Generating Message Header Files (Adding Custom Messages) refer to: http://wiki.ros.org/rosserial/Tutorials/Adding%20Other%20Messages

rosserial_client package is used to generate header files for messages.
Generated messages will be added to ros_lib folder in arduino libraries subpath.
(delete ros_lib  if it exists prior to installing rosserial_client package)

    rm -r ~/sketchbook/libraries/ros_lib
    rosrun rosserial_client make_libraries.py ~/sketchbook/libraries
