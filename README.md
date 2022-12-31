# Call-Recording-Solutions

Different approaches for Call Recording on Android

# Signed roms and unsigned roms

The first main difference we have is between signed roms either by LineageOS or by a dev that is making personal builds signed by self, in our current situation the app com.android.dialer can only be updated using an unofficial build signed by Android.

What we are looking for is auto call-recording capabilities in LineageOS roms, without human intervention in the call recording process, that can be also achieved by using Magisk modules.

# Magisk

A very good and clean Magisk module to do call recording is BCR:

https://github.com/chenxiaolong/BCR

Another approach is using LSPosed, by hooking com.android.dialer, that allows us to get the same result as using a modded com.android.dialer

# LSPosed framework:

Currently supported only up to LineageOS 19.1, it is probably the best solution to avoid third-party.

https://github.com/iptux/XCallRecording-xposed

# Modded Dialers:

Various modded dialers are around:

https://github.com/edodson84/Aosp_Dialer_10_Gradle

https://github.com/iamsj7/packages_apps_Dialer

