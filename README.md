CyanogenMod

Getting Started (-jКоличество потоков)

repo init -u git://github.com/Samsung-MSM8916/android.git -b cm-12.1

repo sync -j25

. build/envsetup.sh

lunch

make otatools -j2

make otapackage -j2
