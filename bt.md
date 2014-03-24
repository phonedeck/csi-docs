---
layout: default
title: Installing the Bluetooth Client
---

# Bluetooth Setup

This guide will lead you through the setup process of Phonedeck CSI for Bluetooth enabled phones.

## Minimum Requirements

Currently Bluetooth connection is only supported on OS X 10.8 or higher running on iMac or MacBook devices.

## Pairing your Phone with the Computer

Check if Bluetooth is enabled on your computer. Go to System Preferences, Bluetooth, and make sure that Bluetooth is turned on. Keep this window open during the following steps.

<p class="screenshots">
<a href="/images/bt/system-preferences-apple.png" data-lightbox="pairing1" title="System Preferences in Apple Menu"><img src="/images/bt/system-preferences-apple.png" /></a>
<a href="/images/bt/system-preferences-bt.png" data-lightbox="pairing1" title="Bluetooth in System Preferences"><img src="/images/bt/system-preferences-bt.png" /></a>
<a href="/images/bt/bluetooth-preferences.png" data-lightbox="pairing1" title="Bluetooth Preferences"><img src="/images/bt/bluetooth-preferences.png" /></a>
</p>

Make your phone discoverable. On your iPhone go to Settings, Bluetooth. Turn Bluetooth on and stay on this screen during the following steps. The bottom of the screen should indicate that the device is now discoverable.

<p class="screenshots">
<a href="/images/bt/ios-settings.png" data-lightbox="pairing2" title="Settings on iPhone"><img src="/images/bt/ios-settings.png" /></a>
<a href="/images/bt/ios-bt.png" data-lightbox="pairing2" title="Bluetooth Settings on iPhone"><img src="/images/bt/ios-bt.png" /></a>
</p>

Wait until your computer discovers your phone. Click on Pair when the phone's name appears on the list. Confirm the connection both on the computer and on the phone.

<p class="screenshots">
<a href="/images/bt/bluetooth-pair.png" data-lightbox="pairing3" title="Pair"><img src="/images/bt/bluetooth-pair.png" /></a>
<a href="/images/bt/bt-code.png" data-lightbox="pairing3" title="Pairing Code on Computer"><img src="/images/bt/bt-code.png" /></a>
<a href="/images/bt/bt-code-ios.png" data-lightbox="pairing3" title="Pairing Code on Phone"><img src="/images/bt/bt-code-ios.png" /></a>
</p>

The devices are paired now, you are free to close the settings screens.

## Downloading the Client

Now you are ready to download the small helper app that connects your phone with Salesforce. You can obtain the latest version here:

<p style="text-align: center"><a href="https://phonedeck-storage.s3.amazonaws.com/csi-bluetooth-binaries/Phonedeck%20CSI%20v0.8.dmg" class="button blue">Download for Mac OS X</a></p>

Just click on the disk image you have downloaded and double click on Phonedeck CSI.

## Running the Client for the First Time

Confirm all the security related questions you might get. It is also highly recommended to move the app to the Applications Folder.

<p class="screenshots">
<a href="/images/bt/security-warning.png" data-lightbox="firsttime" title="Security Warning"><img src="/images/bt/security-warning.png" /></a>
<a href="/images/bt/move-to-apps.png" data-lightbox="firsttime" title="Move to Applications"><img src="/images/bt/move-to-apps.png" /></a>
</p>

You can always reach the Preferences of the app by clicking on the Phonedeck CSI icon on the status bar. First link your Salesforce account, then select the phone you have previously paired with the computer.

<p class="screenshots">
<a href="/images/bt/trayicon.png" data-lightbox="setup" title="Preferences Menu"><img src="/images/bt/trayicon.png" /></a>
<a href="/images/bt/preferences.png" data-lightbox="setup" title="Empty Preferences"><img src="/images/bt/preferences.png" /></a>
<a href="/images/bt/salesforce-login1.png" data-lightbox="setup" title="Salesforce Login"><img src="/images/bt/salesforce-login1.png" /></a>
<a href="/images/bt/salesforce-login2.png" data-lightbox="setup" title="Authorizing Phonedeck CSI"><img src="/images/bt/salesforce-login2.png" /></a>
<a href="/images/bt/select-phone.png" data-lightbox="setup" title="Select Phone"><img src="/images/bt/select-phone.png" /></a>
<a href="/images/bt/setup-done.png" data-lightbox="setup" title="Everything Set Up"><img src="/images/bt/setup-done.png" /></a>
</p>

Now you are ready to go. The icon on the status bar indicates the connection state:

<table>
  <tr><td><img src="/images/bt/icon_32x32.png" /></td><td>Setup complete. Phone will automatically be connected when in range.</td></tr>
  <tr><td><img src="/images/bt/icon_ok_32x32.png" /></td><td>Phone is connected and ready.</td></tr>
  <tr><td><img src="/images/bt/icon_warning_32x32.png" /></td><td>Configuration error, see details in the Preferences</td></tr>  
</table>
