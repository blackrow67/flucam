# FluCam

Flyme Camera Port from Meizu 18.

How to add rom?

First:

git clone https://github.com/blackrow67/flucam.git -b beta vendor

common.mk 

$(call inherit-product, vendor/flucam/config.mk)


Working Features:

Normal mode
Video
Pro
Panoroma
Scanner (QR)
Slow motion
Document Setting
Time Lapse Shooting
Slow motion
Super Night
Square
AI
Face Beauty-Portrait

Bugs:
Long Exposure
In android 11 version, no photos are taken with the front camera for now, but the portrait mode works without any problems. For the Meizu X8 model, it is not possible to take pictures with the front and rear cameras in normal mode. I am investigating the cause of this problem.
