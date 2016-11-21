# ROS-Pololu_Open_IMO_Altimu-10
## ACIKLAMA
Bu uygulama pololu AltIMU-10 v4 Gyro, Accelerometer, Compass, and Altimeter (L3GD20H, LSM303D, and LPS25H Carrier) ' in
ROS (Robot operating system) icin olusturulmus test kodlarini icerir. 
<br><br>

## UYGYLAMAYI CALISTIRMAK ICIN

Ilk once programi arduinoya yukleyiniz.<br>
sonra sirayla <br>

==> 'roscore' <br>
==> 'rosrun rosserial_python serial_node.py _port:=/dev/ttyACM0 _baud:=115200' //burada _port sizin ardunionuzun balandigi porttur.<br>
==> 'rostopic echo gyro' <br>

diyerek uygulamayi calistirabilirisiniz.

#Bu bir test uygulamasidir.
