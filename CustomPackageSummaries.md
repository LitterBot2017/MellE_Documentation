#Custom Package Summaries

## planning
Please Just see the [planning](https://github.com/LitterBot2017/planning) repo's readme.

## yolo2
This package runs our image detections. This package publishes a list of detections that other nodes use later.

## object_tracker
I'm not sure if this package is being used but Yolo sometimes loses detections and this maintains a lock on the target if it gets occasionally dropped in frames.

## navigation
This file also contains a lot of the "meat" of the project, and it's where a lot of things are integrated. It reads in the arduino info and also publishes to the arduino. It also processes some of this arduino data, yolo data, joystick data, and more. The Visual Servoing I believe also is handled within this package.