# Speech-Recognition MATLAB Project

This MATLAB project focuses on speech recognition and includes three MATLAB files. The project allows you to extract voice features, perform voice testing, and train the system with user voice data.

## Files

1. **VoiceFeature.m**
   - MATLAB function to extract voice features.
   - Usage: `[xPitch] = VoiceFeatures(data)`

2. **VoiceTesting.m**
   - MATLAB script for testing voice recognition.
   - Requirements: You need to have recorded voice data saved in a database.
   - Usage: Run the script and follow the instructions to record your voice and perform testing.

3. **VoiceTraining.m**
   - MATLAB script for training the voice recognition system.
   - Requirements: You need to have the database initialized with voice data.
   - Usage: Run the script, record your voice, and save the voice data in the database.

## Run the MATLAB scripts as follows:

**For voice testing:**
run voice_testing.m

**For voice training:**
run voice_training.m

## Notes
Make sure you have the required MATLAB Audio Toolbox installed.
Ensure that the database is initialized before running the training or testing scripts.
