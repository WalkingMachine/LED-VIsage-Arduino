# LED-VIsage-Arduino

## Instructions :
Pour activer la communication serial:
rosrun rosserial_python serial_node.py _port:=/dev/ttyACM0

Pour créé le publisher pour parler au arduino:
self.pubEmo = rospy.Publisher('/control_emo', UInt8, latch=True)




