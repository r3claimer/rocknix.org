# :material-progress-check: installtointernal

`installtointernal` is a script available on selected platforms (currently SM6115, SM8250, SM8550, SM8650 and SM8750) that will resize the Android userdata partition and install ROCKNIX to the internal UFS or eMMC. It will reset your Android userdata, like an Android factory reset would do.

Following this process will allow you to enjoy faster ROCKNIX boot times and faster updates. It also particularly improves the experience of installing and running Steam games.

!!! tip "`installtointernal` has been well-tested, however is only recommended for advanced users with the skills to recover their devices should something go wrong."

## Process

SSH into your device and run `installtointernal`.

!!! tip "Read the prompts carefully! Then read them again to make doubly sure you know what you are being asked."

### Prompt 1 - resize Android userdata

You will be prompted "Enter new Android userdata size in GB:". This allows you to nominate the storage space reserved for Android. The remainder will be used for ROCKNIX boot and storage partitions which are now created.

### Prompt 2 - Copy storage

You will be prompted "Copy existing /storage to new STORAGE? [y/N]:". Answering 'y' will copy all folders except `{roms,games-internal,games-external}` from the storage partition on your SD card to the newly created storage partition on internal storage.

### Success

Finally you should see a summary of the new partitions and the message "ROCKNIX Installation to internal UFS was successful. You can now reboot and remove your SD card.".

## Troubleshooting

Coming soon ...