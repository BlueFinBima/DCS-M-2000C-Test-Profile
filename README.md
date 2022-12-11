# M-2000C-Assets
[![CreateHelios16](https://github.com/HeliosVirtualCockpit/M-2000C-Assets/actions/workflows/BuildAssetPackage.yml/badge.svg)](https://github.com/HeliosVirtualCockpit/M-2000C-Assets/actions/workflows/BuildAssetPackage.yml)

Repository to hold Helios Aircraft assets deliverable outside of the main Helios Installer.

The assets, which comprise images, templates and a welcome profile are packaged together in a Helios16 package which is build using a workflow which Github
then zips.  This zip is then added to the Helios Release assets in the Helios project.

The benefits are believed to be as follows:
1. Reduced size of Helios msi package.
1. Reduced number of folders in the Profile Editor Toolbox
1. Only assets for aircraft which the user owns need to be downloaded and installed
1. Delivering as a Helios16 file means that asset installation can be linked to a minimum Helios level
1. Image assets are no longer hidden in a DLL


