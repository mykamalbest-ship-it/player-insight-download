# Player Insight — isolated Tampermonkey update test

This folder contains ONLY a harmless standalone update-channel test, not Player Insight source code.

1. Install `Player_Insight_Update_Test.user.js` from the raw GitHub URL.
2. Confirm version `0.0.1` in Tampermonkey.
3. Only after confirmation, update both files to version `0.0.2` and run Tampermonkey's check for updates.
4. Verify the existing test script changes to `0.0.2` without creating a duplicate.

The test script matches only `https://example.com/*`, uses no special permissions, and does not access admin sites.

Stable `4.0.0` is NOT published by this test.
