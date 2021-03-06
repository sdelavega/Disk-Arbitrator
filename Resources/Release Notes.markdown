## Disk Arbitrator Release Notes <br/> v0.4.2

#### 0.4.2 11/23/2012

* Added Developer ID signature for Gatekeeper.
* Updated for Xcode 4.5 (should have no affect on behavior).
* Removed PPC architecture.

#### 0.4.1

* Added feature to install/uninstall a launchd agent plist.
* Added labels and tool tips to make mount options easier to understand.

#### 0.4.0

* Fixed overwriting AppLogLevel preference at startup.
* Added log message for mount approval callback.
* Activate application when showing the main window, Preferences, or About panel.
* Changed Attach Disk Image icon.
* Changed mode and activation state to persist across application restart.
* Enabled Sudden Termination (new in Snow Leopard for faster shutdowns).

#### 0.3.2 8/23/2010

* Fixed use of Snow Leopard API to retrieve disk icons.
* Minor code cleanup.

#### 0.3.1 8/9/2010

* Added Preferences window and an option to show the main window at launch.

#### 0.3.0 3/29/2010

* Added Attach Disk Image feature.
* Added check for encrypted disk image.
* Added support for attaching a disk image by dragging the file into the disks window.
* Added a progress window while a disk image is verified.
* Added disk menu to the status item menu.
* Improved validation of toolbar items.

#### 0.2.0 2/14/2010

* Added Disk Info window.
* Added mounting feature with dialog for options and mountpoint path.
* Added unmounting and ejecting.
* Added toolbar and custom icons.
* Improved logging.

#### 0.1.1 2/7/2010

* Added target to build the distribution DMG.
* Fixed refresh bug when a disk is mounted or unmounted.
* Added controls to the main window to activate and change mode.

#### 0.1.0 1/31/2010

* Initial release
