# Rewear 0.1.0 — download candidate

Download `rewear-0.1.0.zip` from this branch and extract it to a permanent folder.

1. Open chrome://extensions in Chrome or Chromium.
2. Enable Developer mode.
3. Choose Load unpacked and select the extracted folder containing manifest.json.

This is a candidate build, not a certified production release. It provides product extraction, contextual secondhand marketplace search links, local favorites and Dutch/English/French settings. It does not retrieve verified live marketplace offers. No backend, account or paid API is required.

65 automated unit/integration tests and 15 production-bundle browser-harness checks passed. Actual extension installation could not be tested in the build environment because managed Chromium policy blocks new extensions. Live retailer and marketplace verification was blocked by network policy. Marketplace destinations still require live verification.

Verify the ZIP with the accompanying SHA-256 file. This branch contains the download package only; it does not replace the source working tree. This is not a Chrome Web Store publication.
