# Steps to reproduce

1. Install node modules with `yarn`
2. `eas build --local --profile development --platform ios`
3. Inspect the generated build's Expo.plist to see `EXUpdatesCodeSigningCertificate` has been dropped.
