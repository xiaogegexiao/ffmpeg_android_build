# ffmpeg_android_build
Build ffmpeg lib for Android using NDK r13b

# Notice
Please note that this is for building ffmpeg on Mac OS with Android NDK r13b (Please just use this version, if you don't have, please download one)

# Steps 
Follow these steps to compile ffmpeg with openssl for Android
> 1, At the beginning, we should setup $ANDROID_NDK for the MacOS in ~/.bash_profile to the new downloaded Android NDK r13b  
> 2, Edit ~/.bash_profile, add `export ANDROID_NDK=/Users/admin/Downloads/android-ndk-r13b`  
> 3, `source ~/.bash_profile`  
> 4, `git clone https://xiao-nirovision@bitbucket.org/nirovision/nostalgia-android-ffmpeg.git`  
> 5, `cd ffmpeg_android_build`  
> 6, `sh android_build.sh`  
> 7, Check out the generated ffmpeg static and shared libs  

# TLSv1.2 negotiation fails with OpenSSL
When encoutering `Unable to negotiate TLS/SSL session`, please refer to http://git.videolan.org/?p=ffmpeg.git;a=blobdiff;f=libavformat/tls_openssl.c;h=178ca9e0e4684402cbcadfa5ab10136aceec4f76;hp=c551ac74e24b2bdbf7a41fa0024a2d46d4ea9bf1;hb=e8634fb92e2f624f19ee5fced6481d8ece503119;hpb=121be310607879841d19a34d9f16d4fe9ba7f18c

Please let me know if you encounter any issue