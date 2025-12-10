# StosVPN

A VPN for SideStore and StikJIT that is much stabler and supports offline JIT Enabling.

## Download IPA

You can download the latest IPA build from GitHub Actions:

1. Go to the [Actions tab](../../actions) in this repository
2. Click on the latest successful "Build IPA with Fake Signing" workflow run
3. Scroll down to the "Artifacts" section
4. Download the `StosVPN-IPA` artifact
5. Extract the ZIP file to get `StosVPN-fakesigned.ipa`

Alternatively, trigger a new build manually:
1. Go to the [Actions tab](../../actions)
2. Click on "Build IPA with Fake Signing" workflow
3. Click "Run workflow" button
4. Select the branch and click "Run workflow"
5. Wait for the build to complete and download the artifact

**Note:** The IPA is fake-signed using `ldid` and is intended for use with SideStore or similar sideloading tools.
