^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package pal_msgs
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.9.1 (2014-05-27)
------------------
* Update meta-package with pal_walking_msgs and pal_navigation_msgs
* Remove unneeded package text_to_speech
  Its functionalities (Sound action) have been merged
  into pal_interaction_msgs in the previous commit.
* Update metapackage
* Add pal_device_msgs
* Added other packages needed by people that want to use our robot, face
  detection in pal_detection_msgs, and text to speech in text_to_speech. Also
  removed from pal_interaction_msgs the references to the speech part that was
  included there and made incompatible the use of axclient without having the
  same package name than the one inside of the real robot
* Add pal_interaction_msgs and metapackage
* Contributors: Paul Mathieu, Sammy Pfeiffer
