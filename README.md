# Visualizing a Point Cloud Using Scene Depth

Place points in the real-world using the scene's depth data to visualize the shape of the physical environment.
This repository distributes the point cloud sample code that Apple released at WWDC20, with the addition of the smoothedSceneDepth feature.

## Overview

- Note: This sample code project is associated with WWDC20 session [10611: Explore ARKit 4](https://developer.apple.com/wwdc20/10611/).

Please refer to the following URL for the original code.
- https://github.com/artemnovichkov/wwdc20-samplecode/tree/master/VisualizingAPointCloudUsingSceneDepth

Or, for Apple's description of smoothedSceneDepth and sample code, please refer to the following URL.
- https://developer.apple.com/documentation/arkit/environmental_analysis/displaying_a_point_cloud_using_scene_depth

## Configure the Sample Code Project

Before you run the sample code project in Xcode, set the run destination to an iPad Pro with a LiDAR sensor, running iPadOS 14.0 or later.
The smoothedSceneDepth feature currently only works on the iPad Pro (5th generation), but in the future it will also work on iPhones equipped with LiDAR.
