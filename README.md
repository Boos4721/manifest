## Auto-Syncing manifest for the Huawei Y6 - Scale

After/Before you synced the Rom tree run this command:

    $ git clone https://github.com/Boos4721/manifest.git -b aex.8.1 .repo/local_manifests

Then sync up with the command: repo sync --force-sync --no-tags --no-clone-bundle

That will download all of the device specific files of the Huawei Y6.

