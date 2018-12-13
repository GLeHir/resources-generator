# Presentation

Made for mobile apps developers, this script will generate app icon & splashscreen assets of all sizes (supports iPhone, iPad & Android). 

Images will be generated in the ./res/{platform}/ folder and will be ready to be imported to Android Studio and Xcode projects.

# Installation

This tool requires faslane

    gem install fastlane



# How to use

Put your source images in the ./res folder :
 
- icon.png (1024x1024)    
- splash.png (4096x4096) 
 


 
###  Generate all assets 

    bundle exec fastlane mac assets

###  Generate splashscreens

    bundle exec fastlane mac splash

###  Generate icons

    bundle exec fastlane mac icons
