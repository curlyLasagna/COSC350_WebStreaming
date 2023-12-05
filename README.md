# Video Surveillance and Web Streaming

## What this project accomplishes 

This project enables motion detection using an algorithm called background subtraction

## Setting up the project

### Requirements

- Raspberry Pi
- SSH key
- Webcam
- (optional) Ethernet cable

### SSH with X11 Forwarding

Carrying peripherals would've been pointless

#### Mac OS

1. Install [XQuartz](https://www.xquartz.org/) via brew  
- `brew install xquartz`

2. `ssh -X cosc350@raspy`
- If Pi is hardwired to Mac: `ssh -X cosc350@raspy.local`

### Dependencies

- Poetry
- Flask

1. Install [Poetry - Python dependency management and packaging made easy](https://python-poetry.org/)

**WIP**