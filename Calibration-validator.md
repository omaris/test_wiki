The validation tool extracts calibration targets on ROS image streams and displays the image overlaid with the reprojections of the extracted corners. Further the reprojection error statistics are calculated and displayed for mono and inter-camera reprojection errors.

The tool must be provided with a camera-system calibration file and a configuration for the calibration target. The output YAML of the multi-camera calibrator can be used as the camera-system configuration.

Usage:
> kalibr_camera_validator --cam camchain.yaml --target target.yaml
