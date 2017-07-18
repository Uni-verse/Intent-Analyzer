# Intent-Analyzer
A single webpage application tool used to analyze/parse oem intent log files

FEATURES: 

+ Detecting Duplicate Intents being broadcasted
+ Counting Intent types

DEPENDENCIES: 

+ Android Debug Bridge/Command Line Tools (Recommended)
+ T-Mobile Prod logging APK installed.
+ T-Mobile App - All Permissions Enabled.
+ Agree to T-Mobile Diagnostics T&C
+ Developer Options > USB Debugging enabled.

HOW TO USE: 

Open page in browser, preferrably Chrome. Open file log or paste content into the textarea. Click scan button.

ADB PULL 

$ adb shell ls /storage/self/primary/debug_logs/intent_logs.txt

$ adb pull /storage/self/primary/debug_logs/intent_logs.txt <filename.txt>

