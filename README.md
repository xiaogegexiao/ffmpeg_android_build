# ffmpeg_android_build
Build ffmpeg lib for Android using NDK r13b

# Notice
Please note that this is for building ffmpeg on Mac OS with Android NDK r13b (Please just use this version, if you don't have, please download one)

# Steps 
Follow these steps to compile ffmpeg with openssl for Android
> 1, At the beginning, we should setup $ANDROID_NDK for the MacOS in ~/.bash_profile to the new downloaded Android NDK r13b

> 2, Edit ~/.bash_profile, add `export ANDROID_NDK=/Users/admin/Downloads/android-ndk-r13b`

> 3, `source ~/.bash_profile`

> 4, `git clone https://github.com/xiaogegexiao/ffmpeg_android_build.git`

> 5, `cd ffmpeg_android_build`

> 6, `sh android_build.sh`

> 7, Check out the generated ffmpeg static and shared libs


Please let me know if you encounter any issue