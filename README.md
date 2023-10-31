# qos_profile
pointcloud_to_laserscanを使用して，3次元点群を2次元点群に圧縮した際には，以下のようにros2 bagを再生することで，rviz2で/scan単体での可視化できるようになる．
'''
cd
ros2 bag play <bagfile_name> --qos-profile-overrides-path ~/scan_qos.yaml
'''
