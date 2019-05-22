# Downloads

Dataset sequences can be downloaded from [here](http://oscar.skoltech.ru/data/). Sequences can contain the following files:
- `left.tar` and `right.tar`: frames from left and right cameras respectively compressed using lossless algorithm. Each file inside tar archive is named as `<unix timestamp, us>_<monotonic clock, us>.flif`. For converting frmaes to PNG, PNM or JPEG, you can use `convert` utility from [here](https://github.com/SkoltechRobotics/oscar-cli). Please referer to the paper for more details.
- `left_jpgs.tar` and `right_jpgs.tar`: frames with applied histogram equalization filter compressd using JPEG lossy compression.
- `left_video.webm` and `right_video.webm`: video assembled from frames after with applied histogram equalization.
- `velodyne.pcap.xz`: compressed network packets from Velodyne HDL-64E S3 LiDAR.
- `imu.bin.xz`: InertiaCube3 IMU data.
- `gps.log.xz`: GPS NMEA messages from Garmin 18x receiver.

# Annotations

Traffic sign annotations can be downloaded from https://github.com/icevision/annotations/.

# License
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Dataset" property="dct:title" rel="dct:type">IceVisionSet</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName"><a href="https://www.skoltech.ru/">ISR Lab, Skoltech</a> & <a href="https://www.rvc.ru/">RVC</a></span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="http://oscar.skoltech.ru" rel="dct:source">http://oscar.skoltech.ru/</a>.
