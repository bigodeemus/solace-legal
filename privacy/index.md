---
layout: default
title: Solace Privacy Policy
---

[Solace Legal & Support](../) · [Support](../support/)

# Solace Privacy Policy

Effective date: September 1, 2026
Last updated: September 1, 2026

Solace is a personal financial-planning and household cash-flow application provided by **Derrek Wilson** ("Solace," "we," "us," or "our"). This policy explains what information Solace handles, where that information is stored, who can access it, and the choices available to users.

## The short version

The Solace developer does not operate a server that receives users' financial-planning data and cannot view users' private CloudKit records. Solace does not sell personal information, display advertising, use third-party analytics or advertising SDKs, or track users across apps or websites.

Solace stores data on the user's device and in Apple's iCloud and CloudKit services. A personal profile stays in the user's private CloudKit database. A shared profile is available only to the owner and the Apple Account users whom the owner invites and who accept the invitation.

## Information users provide to Solace

Users may enter or create:

- a Solace display name and the names of people represented in a profile;
- income, expenses, payment dates, payment status, forecasts, confirmed amounts, and notes;
- account-fund and reserve amounts, contribution allocations, deferrals, and related cash-flow information;
- annual plans, payment cycles, plan subplans, and historical planning records; and
- shared-profile membership, roles, and contribution-sharing rules.

Solace uses this information only to provide the planning, calculation, device synchronization, purchase-entitlement, and user-directed collaboration features of the app.

Solace does not ask for or connect to bank-login credentials, full payment-card numbers, government identifiers, contacts, photographs, precise location, microphone recordings, or camera data. Solace does not initiate bank transfers, pay bills, move money, provide loans, trade securities, or provide financial, investment, tax, or legal advice.

## Apple Account and device authentication

Solace requires an Apple Account signed in to iCloud for its CloudKit features. Apple gives the app an account-scoped CloudKit identifier so Solace can associate the correct private and shared records with the current iCloud user. Solace does not receive the user's Apple Account password or Apple Account email address through this process.

Solace can use Face ID, Touch ID, or the device passcode or password to unlock the app. Authentication is performed by Apple's Local Authentication framework. Solace receives only whether authentication succeeded and does not receive or store biometric data.

## Storage and synchronization

Solace stores a local working copy of app data in the app's sandbox on each device. It also stores structured records in Apple's CloudKit service so the user's devices can synchronize through iCloud.

Solace may register for silent CloudKit change notifications so it can learn that private or shared records changed and refresh them automatically. These background notifications are delivered by Apple, do not display a user-facing alert, and do not route the user's financial-planning records through a developer-operated notification server. Because background delivery is not guaranteed, Solace also checks for changes when the app becomes active and when the user requests synchronization.

Personal profiles are stored in the current user's private CloudKit database. By default, private CloudKit records are accessible only to that user and are not visible to the Solace developer through the CloudKit developer portal. Solace does not use a public CloudKit database for financial-planning records.

A shared profile is stored in a separate CloudKit record zone owned by the profile owner. When the owner uses Apple's CloudKit sharing interface to invite another Apple Account user, an invited participant who accepts can access and edit the records in that shared profile according to the permissions provided by the app and Apple. Sharing a profile does not expose either participant's separate personal profile.

CloudKit data is handled by Apple under the user's iCloud relationship with Apple and is subject to Apple's terms, privacy policy, security, availability, and storage limits.

## Solace Pro purchases

Apple processes Solace Pro purchases through the App Store. Solace uses StoreKit to verify whether the Apple Account has an active Solace Pro entitlement. The Solace developer does not receive the user's payment-card number. Apple may provide the developer with sales, proceeds, and transaction reports under Apple's developer agreements; those reports do not include the user's Solace financial-planning records.

## Shared profiles and other users

Creating or joining a shared profile is optional and user directed. Before sharing, users should understand that accepted participants can view the financial and profile information stored in that shared profile and may be able to edit it. Users should share only with people they trust.

The profile owner can manage participants or stop sharing through Apple's CloudKit sharing interface. A participant can leave a shared profile. Removing a participant or ending a share prevents future access through CloudKit, but it cannot erase screenshots or other copies a participant may have made outside Solace while access was available.

## Tracking, advertising, analytics, and sale of data

Solace does not:

- track users across apps or websites;
- display third-party advertising;
- include third-party advertising or analytics SDKs;
- sell or rent personal information; or
- transmit financial-planning data to a developer-operated analytics, advertising, or financial-data server.

If these practices change in a future version, this policy and the App Store privacy label will be updated before the changed version is released.

## Support communications

If a user voluntarily contacts Solace support outside the app, we receive the contact details and message content the user chooses to provide. Users should not send bank credentials, complete payment-card numbers, or financial records in a support message.

Support correspondence is used only to respond to the request, investigate a reported issue, maintain necessary support records, and comply with legal obligations. It is normally retained for no longer than 12 months after the last exchange, unless a longer period is reasonably necessary for an active dispute, security matter, or legal obligation. A user may request earlier deletion of support correspondence by contacting us, subject to any information we are legally required to retain.

Solace does not currently include an in-app support form, automatic log upload, or remote diagnostic service.

## Profile export

People & Funds provides separate export controls for personal and shared profiles. When a user chooses Export Profile, Solace creates a readable JSON copy of only that selected profile and presents the operating system's save interface. The user chooses where the file is stored or shared; Solace does not automatically send the export to the developer or another service.

Exports include the financial-planning data, participant names, and notes contained in the selected profile. They exclude CloudKit record identifiers, synchronization change tokens, and App Store purchase-entitlement state. A person who can access a shared profile may export its contents, so users should share profiles and exported files only with people they trust. Exported files are outside Solace's managed storage and remain the user's responsibility to protect and delete.

## Retention and deletion

Local Solace data remains on a device until it is deleted through Solace, the app's data is removed, or the app is uninstalled in a way that removes its local container.

CloudKit data remains in iCloud until the user deletes it through Solace or it is otherwise removed under the user's iCloud settings and Apple's retention practices.

Solace provides a **Delete Solace Data** control in People & Funds. After confirmation, the deletion process:

- deletes the current Apple Account's private Solace account record and private profile zones;
- stops CloudKit shares owned by that user;
- leaves other users' shared-profile records intact while ending this user's access to accepted shares;
- removes the device's local Solace database; and
- does not cancel or delete the user's App Store purchase history or Solace Pro entitlement, which Apple manages separately.

Each profile card also provides a profile-scoped deletion control. Deleting a personal profile does not delete shared profiles. When a shared-profile owner deletes a shared profile, its CloudKit zone, financial records, and invitation are permanently removed for every participant. When an invited participant chooses deletion for a shared profile, that participant leaves the share and loses access; the owner's records remain, the owner becomes the sole active user, and the owner can invite someone else.

For an owned profile, Solace first removes the profile from the Apple Account's CloudKit index so linked devices no longer discover it, then deletes its record zone. If final zone cleanup is temporarily interrupted, Solace reports cleanup as pending and retains only the minimal request required to retry it. Solace does not restore the deleted profile while cleanup is pending.

## Security

Solace uses Apple platform protections including app sandboxing, device authentication, code signing, and iCloud and CloudKit access controls. Users are responsible for protecting their devices, Apple Accounts, and invitations. No storage or transmission system can be guaranteed to be completely secure.

## Children's privacy

Solace is a general-audience financial-planning app and is not directed to children under 13. The developer does not knowingly collect children's personal information through the app.

## Legal requests

Because the developer cannot access users' private CloudKit financial-planning records, requests concerning those records may need to be directed to Apple or handled by the user through their own account controls. If we are legally required to disclose information that we actually possess, such as support correspondence, we will disclose only what the law requires.

## Changes to this policy

We may update this policy to reflect changes to Solace, Apple platform services, or legal requirements. The effective date above will be updated, and material changes will be communicated in the app when appropriate. A release that changes the developer's data-collection practices will also be reflected in the App Store privacy label.

## Contact

Privacy and support questions: [djwilsonspectra@gmail.com](mailto:djwilsonspectra@gmail.com)  
Developer: **Derrek Wilson**
