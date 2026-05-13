# Kronosteam

Kronosteam is the Centris Events product stack for the mobile apps, web dashboard,
API, and release/deployment tooling used across the platform.

## Main repositories

| Repository | Purpose | Key docs |
|---|---|---|
| [android](https://github.com/centris-events/android) | Android app, Gradle build, fastlane lanes, Firebase distribution, Play release workflow | [Android CI/CD](https://github.com/centris-events/android/blob/master/docs/android-release.md) |
| [ios](https://github.com/centris-events/ios) | iOS app, CocoaPods workspace, fastlane lanes, TestFlight and App Store release workflow | [iOS CI/CD](https://github.com/centris-events/ios/blob/master/docs/ci-cd.md) |
| [dashboard](https://github.com/centris-events/dashboard) | Yii2/PHP web dashboard, backend/admin/API surfaces, Docker local stack, deployment automation | [README](https://github.com/centris-events/dashboard/blob/master/README.md), [docs index](https://github.com/centris-events/dashboard/blob/master/docs/README.md) |
| [php](https://github.com/centris-events/php) | Shared multi-arch Docker PHP image used by the dashboard stack | [README](https://github.com/centris-events/php/blob/master/README.md) |

## Platform overview

| Area | Stack |
|---|---|
| Mobile apps | Android, iOS, Firebase, fastlane |
| Web/API | PHP, Yii2 advanced app, OAuth2, Codeception |
| Infrastructure | Docker Compose, Traefik, OVH registry, OVH OKMS-backed secrets |
| Storage and integrations | Cloudinary, Firebase, S3-compatible storage, SendGrid |
| Delivery | GitHub Actions for app validation, release archives, dashboard deploys, server bootstrap, rollback, and SSH key maintenance |

## Operational docs

- [Dashboard environments](https://github.com/centris-events/dashboard/blob/master/docs/environments.md)
- [Dashboard release process](https://github.com/centris-events/dashboard/blob/master/docs/release-process.md)
- [Dashboard deployment guide](https://github.com/centris-events/dashboard/blob/master/docs/deployment-guide.md)
- [Dashboard server setup](https://github.com/centris-events/dashboard/blob/master/docs/server-setup.md)
- [Dashboard naming conventions](https://github.com/centris-events/dashboard/blob/master/docs/naming-conventions.md)
- [Android OKMS secrets](https://github.com/centris-events/android/blob/master/docs/ovh-okms-secrets.md)
- [iOS OKMS secrets](https://github.com/centris-events/ios/blob/master/docs/ovh-okms-secrets.md)
- [Dashboard OKMS secrets](https://github.com/centris-events/dashboard/blob/master/docs/ovh-okms-secrets.md)

## Admin services

- [Firebase](https://console.firebase.google.com/) for app distribution, messaging, analytics, Crashlytics, and Cloud Functions
- [Google Play Console](https://play.google.com/console/) for Android releases
- [App Store Connect](https://appstoreconnect.apple.com/) for iOS releases, TestFlight, and App Store submissions
- [Apple Developer](https://developer.apple.com/account/) for certificates, identifiers, profiles, and team access
- [OVHcloud Manager](https://www.ovh.com/manager/) for infrastructure, container registry, and OKMS secrets
- [Cloudinary](https://cloudinary.com/console/) for media storage and delivery
- [SendGrid](https://app.sendgrid.com/) for email delivery

## Quick links

- [All repositories](https://github.com/orgs/centris-events/repositories)
