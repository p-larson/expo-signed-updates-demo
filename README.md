# Steps to reproduce

1. `eas build --local --profile development --platform ios`
2. Inspect the generated build's Expo.plist to see `EXUpdatesCodeSigningCertificate` has been dropped.
