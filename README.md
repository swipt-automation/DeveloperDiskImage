# DeveloperDiskImage

The iOS Developer Disk Image that Swipt mounts on the device, cryptex variant only.

Taken from Xcode 27.2 (DDI build 27B52): `Contents/Resources/Packages/XcodeSystemResources.pkg`, `Library/Developer/CoreDevice/CandidateDDIs/iOS_DDI.dmg`, `Restore/`. The personalized variant and `Restore.plist` are left out, and the asset files are renamed to the fixed `Image.dmg*` names.

It is published to npm as `@swipt/developer-disk-image` by the workflow of swipt-automation/swipt, where this repository is the submodule `Swipt/Resources/DeveloperDiskImage`. Its version is the Xcode version: 27.2.0 for Xcode 27.2. A newer disk image from the same Xcode version raises the patch number.

To update, replace the files with those of a newer Xcode, note its version here, and set the version in `package.json`.
