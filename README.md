## Auto-Syncing manifest for the Huawei P8 Lite - Alice

After/Before you synced the Rom tree run this command:

    $ git clone https://github.com/Huawei-P8-Lite/manifest.git -b cm-14.1 .repo/local_manifests

Then sync up with the command: repo sync --force-sync --no-tags --no-clone-bundle

That will download all of the device specific files of the Huawei P8 Lite.

