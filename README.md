# Nex2Me-Plan

Plan will provide forward look and clear objectives for each week to achieve Nex2Me product launch

Week wise plan - 21 Sep 2020 to 26 Sep 2020

Android: 
1. Complete scripts to upload test data. Provide build#2 for testing with critical defects fixed.
2. Complete integration of the following into the full app and give build#3
  * Remove noise from MIC audio, Playing track speaker position so that track should not record with audio (almost completed) 
  * Audio mixing & mixed audio mixing to video.
  * Mediapipe new pipeline. 
  * Content Moderation (less priority compared to others)
  * FFMPEG image compression
  * App size optimization to bring it under 100 MB -first level optimization

iOS: (sizing of the tasks are not done. Madhavi, please confirm the possibility)
1. Upload current build#1 to App store for testing.
2. Write code and prove : Audio mixing & mixed audio mixing to video (in progress)
3. Write code and prove : Pipeline for running Detection, Segmentation, Compositon/Super Resolution models.
4. Write code and prove : Remove noise from MIC audio, Playing track speaker position so that track should not record with audio
5. Write code and prove : FFMPEG image compression.

Testing:
1. Android App : Test round#1 : 
  * Continue with writing test scenarios and testing with build#1. 
  * Test build#2 along with lot of test data to check explore, search, i'm in functionality.
  * Test build#3 with specific focus on primary, secondary, broadcast primary, broadcast secondary, i'am in functionality

2. iOS App: Test round#1 
  * Test build#1 primarily focus on login/signup, home screen, explore, search, notifications, profile, tracks, campaign etc.

Deep Learning Models:
1. Prove that models (segmentation, detection and combined model for composition & super resolution) are running in iOS.
2. Complete full training with speed and quality optimization for Composite & Super Resolution models.
3. Achieve temporal stability for Segmentation model with suitable run time efficiency.
4. Achieve milestone#2 of full pipeline of models in Android and iOS with speed and quality. Further optimization will be done subsequently.
