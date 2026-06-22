# BYOD
- The code in 'byod.py' has been written and structured in the same format as the below tables
- Each section of code is also commented witht eh name of the tabe on this ReadME, e.g. General
# iOS Restrictions

## General
| Setting | XML Key | Value |
|---|---|---|
| Allow Camera | `allowCamera` | Yes |
| Allow Device Sleep | `allowDeviceSleep` | Yes |
| Allow FaceTime | `allowVideoConferencing` | Yes |
| Allow Handoff | `allowActivityContinuation` | Yes |
| Allow Screenshots and Screen Recording | `allowScreenShot` | Yes |
| Allow Setting Up New Devices via Proximity | `allowProximitySetupToNewDevice` | No |
| Allow Voice Dialing | `allowVoiceDialing` | No |
| Classroom: Allow Unprompted App and Device Lock | `forceClassroomUnpromptedAppAndDeviceLock` | No |
| Classroom: Allow Unprompted Screen Observation | `forceClassroomUnpromptedScreenObservation` | No |
| Classroom: Automatically Join Classes | `forceClassroomAutomaticallyJoinClasses` | No |
| Classroom: Require Permission to Leave Classes | `forceClassroomRequestPermissionToLeaveClasses` | No |
| Force Automatic Date & Time | `forceAutomaticDateAndTime` | No |

## Lock Screen
| Setting | XML Key | Value |
|---|---|---|
| Allow Control Center on Lock Screen | `allowLockScreenControlCenter` | Yes |
| Allow Notification Center on Lock Screen | `allowLockScreenNotificationsView` | Yes |
| Allow Today View on Lock Screen | `allowLockScreenTodayView` | Yes |
| Allow Wallet (Passbook) on Lock Screen | `allowPassbookWhileLocked` | Yes |

## USB & Pairing
| Setting | XML Key | Value |
|---|---|---|
| Allow Pairing with Non‑Configurator Hosts | `allowHostPairing` | Yes |
| USB Restricted Mode (Disallow USB Accessories While Locked) | `allowUSBRestrictedMode` | No |

## Apps
| Setting | XML Key | Value |
|---|---|---|
| Allow App Clips | `allowAppClips` | Yes |
| Allow App Installation via App Store | `allowUIAppInstallation` | Yes |
| Allow Automatic App Downloads | `allowAutomaticAppDownloads` | Yes |
| Allow iMessage | `allowChat` | Yes |
| Allow Installing Apps | `allowAppInstallation` | Yes |
| Allow Removing Apps | `allowAppRemoval` | Yes |
| Allow Removing System Apps | `allowSystemAppRemoval` | Yes |
| Allow Trusting New Enterprise App Authors | `allowEnterpriseAppTrust` | Yes |
| Restrict App Usage | `allowListedAppBundleIDs` | No |

## Managed Open-In
| Setting | XML Key | Value |
|---|---|---|
| Allow Documents from Managed Sources in Unmanaged Destinations | `allowOpenFromManagedToUnmanaged` | No |
| Allow Documents from Unmanaged Sources in Managed Destinations | `allowOpenFromUnmanagedToManaged` | Yes |
| Allow Managed Apps to Store Data in iCloud | `allowManagedAppsCloudSync` | No |
| Treat AirDrop as Unmanaged Destination | `forceAirDropUnmanaged` | Yes |

## iCloud
| Setting | XML Key | Value |
|---|---|---|
| Allow iCloud Backup | `allowCloudBackup` | Yes |
| Allow iCloud Drive (Documents & Data) | `allowCloudDocumentSync` | Yes |
| Allow iCloud Keychain | `allowCloudKeychainSync` | No |
| Allow iCloud Photos | `allowCloudPhotoLibrary` | Yes |
| Allow My Photo Stream | `allowPhotoStream` | Yes |
| Allow Shared Albums | `allowSharedStream` | Yes |

## Safari
| Setting | XML Key | Value |
|---|---|---|
| Allow Safari | `allowSafari` | Yes |
| Safari: Accept Cookies | `safariAcceptCookies` | Yes |
| Safari: Allow AutoFill | `safariAllowAutoFill` | Yes |
| Safari: Allow JavaScript | `safariAllowJavaScript` | Yes |
| Safari: Allow Pop‑ups | `safariAllowPopups` | No |
| Safari: Fraudulent Website Warning | `safariForceFraudWarning` | Yes |

## AirPrint
| Setting | XML Key | Value |
|---|---|---|
| Allow AirPrint | `allowAirPrint` | Yes |
| Allow AirPrint Credentials Storage | `allowAirPrintCredentialsStorage` | Yes |
| Allow AirPrint iBeacon Discovery | `allowAirPrintiBeaconDiscovery` | Yes |
| Require Trusted TLS for AirPrint | `forceAirPrintTrustedTLSRequirement` | Yes |

## Notifications
| Setting | XML Key | Value |
|---|---|---|
| Allow Notifications Settings Modification | `allowNotificationsModification` | yes |

## Files
| Setting | XML Key | Value |
|---|---|---|
| Allow Files Access to Network Drives | `allowFilesNetworkDriveAccess` | Yes |
| Allow Files Access to USB Drives | `allowFilesUSBDriveAccess` | Yes |

## Apple Watch
| Setting | XML Key | Value |
|---|---|---|
| Allow Pairing with Apple Watch | `allowPairedWatch` | Yes |
| Force Apple Watch Wrist Detection | `forceWatchWristDetection` | No |

## Network & Connectivity
| Setting | XML Key | Value |
|---|---|---|
| Allow Adding VPN Configurations | `allowVPNCreation` | No |

## Security & Privacy
| Setting | XML Key | Value |
|---|---|---|
| Allow Enabling Restrictions (Screen Time) | `allowEnablingRestrictions` | Yes |
| Allow Erase All Content and Settings | `allowEraseContentAndSettings` | No |
| Allow Find My | `allowFindMyDevice` | Yes |
| Allow Find My Friends/People | `allowFindMyFriends` | No |
| Allow Installing Configuration Profiles (UI) | `allowUIConfigurationProfileInstallation` | No |
| Allow Passcode Modification | `allowPasscodeModification` | Yes |
| Allow Password AutoFill | `allowPasswordAutoFill` | Yes |
| Allow Password Sharing | `allowPasswordSharing` | No |
| Allow Personalized Ads by Apple | `allowApplePersonalizedAdvertising` | No |
| Allow Proximity‑based Password Sharing Requests | `allowPasswordProximityRequests` | No |
| Allow Sending Diagnostic Data to Apple | `allowDiagnosticSubmission` | No |
| Allow Touch ID Fingerprint Modification | `allowFingerprintModification` | Yes |
| Allow Touch ID for Unlock | `allowFingerprintForUnlock` | Yes |
| Allow Unpaired External Boot to Recovery | `allowUnpairedExternalBootToRecovery` | No |
| Allow Untrusted TLS Certificate Prompt | `allowUntrustedTLSPrompt` | No |
| Force Encrypted Backups | `forceEncryptedBackup` | Yes |
| Force Limit Ad Tracking | `forceLimitAdTracking` | Yes |
| Modify Account Settings | `allowAccountModification` | Yes |
| Require Face ID / Touch ID Before AutoFill | `forceAuthenticationBeforeAutoFill` | Yes |

## Software Updates
| Setting | XML Key | Value |
|---|---|---|
| Defer Software Updates | `forceDelayedSoftwareUpdates` | No |

## Siri
| Setting | XML Key | Value |
|---|---|---|
| Allow Siri While Locked | `allowAssistantWhileLocked` | No |




# Reasons for changes from guidelines
- Allow Notification Center on Lock Screen - See any notifications quickly
- Allow Today View on Lock Screen - Some people may use it to quickly see their widgets, including notes and reminders, rather than unlocking their device
- Allow Control Center on Lock Screen - Some people may want to be able to want to quickly control their device, including turning brightness down

- Allow pairing with Non-configurator Hosts -
- USB restricted mode - If large sets of data are needed to be downloaded while the user is not close, so can not keep it unlocked

- Allow Installing Apps - Users should be able to download what they want to on their personal device
- Allow Trusting New Enterprise App Authors - Users shouldnt be restricted to newer apps on their personal devices
- Restricted App Usage - Allow the user to use all apps

- Allow Documents from Unmanaged Sources in Managed Destinations - Documents or photos from the users device so the process can be faster and more efficent while being safe

- Allow iCloud Backup - So nothing is lost from their personal device
- Allow iCloud Drive - Allows them to see their personal data and documents
- Allow iCloud Photos - Allows them to use their personal devices photos anywhere
- Allow My Photo Stream - Discontinued on newer devices, allowed for important photos to stay for a while
- Allow Shared Albums - Share personal photos with family memebers or others

- Allow Notifications Settings Modification - Users should be allowed to chose what notifcations happen and when on their personal device

- Allow Files Access to Network Drive - Users should be able to send files online
- Allow Files Access to USB Drives - Users should be able to move files physically

- Allow Pairing with Apple Watch - Users should be able to use their personal watch while connected to their personal device

- Allow Find My - If the user has many connected devices they might want to be able to track their locations
- Modify Account Settings - The user may want to change a personal setting which should not be restricted
