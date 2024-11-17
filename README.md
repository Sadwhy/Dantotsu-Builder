# Weekly Preview Release of Dantotsu

This repository automatically builds [**Dantotsu**](https://github.com/rebelonion/Dantotsu/tree/dev) every **Friday at 6 AM (Standard Time)**.  
You can easily add this build to your [**Obtainium**](https://apps.obtainium.imranr.dev/redirect?r=obtainium://app/%7B%22id%22%3A%22ani.dantotsu%22%2C%22url%22%3A%22https%3A%2F%2Fgithub.com%2FSadwhy%2FDantotsu-Builder%22%2C%22author%22%3A%22Sadwhy%22%2C%22name%22%3A%22Dantotsu%22%2C%22preferredApkIndex%22%3A0%2C%22additionalSettings%22%3A%22%7B%5C%22includePrereleases%5C%22%3Afalse%2C%5C%22fallbackToOlderReleases%5C%22%3Atrue%2C%5C%22filterReleaseTitlesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22filterReleaseNotesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22verifyLatestTag%5C%22%3Afalse%2C%5C%22dontSortReleasesList%5C%22%3Afalse%2C%5C%22useLatestAssetDateAsReleaseDate%5C%22%3Afalse%2C%5C%22releaseTitleAsVersion%5C%22%3Afalse%2C%5C%22trackOnly%5C%22%3Afalse%2C%5C%22versionExtractionRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22matchGroupToUse%5C%22%3A%5C%22%5C%22%2C%5C%22versionDetection%5C%22%3Afalse%2C%5C%22releaseDateAsVersion%5C%22%3Afalse%2C%5C%22useVersionCodeAsOSVersion%5C%22%3Afalse%2C%5C%22apkFilterRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22invertAPKFilter%5C%22%3Afalse%2C%5C%22autoApkFilterByArch%5C%22%3Atrue%2C%5C%22appName%5C%22%3A%5C%22%5C%22%2C%5C%22shizukuPretendToBeGooglePlay%5C%22%3Afalse%2C%5C%22allowInsecure%5C%22%3Afalse%2C%5C%22exemptFromBackgroundUpdates%5C%22%3Afalse%2C%5C%22skipUpdateNotifications%5C%22%3Afalse%2C%5C%22about%5C%22%3A%5C%22%5C%22%7D%22%2C%22overrideSource%22%3Anull%7D).

---

## Annoyances

1. **Manual Build Triggers**  
   Major updates can be triggered manually if needed.  (by me)
2. **Different Signatures**  
   This build uses different signing keys from the official version. As a result:
   - You cannot install both versions simultaneously.  
   - Installing one prevents the other from updating.  
3. **No Empty Releases**  
   Builds are skipped if there are no new commits during the week.

---

## Changes in This Build

- **Performance Optimization**  
  Debugging and Firebase are disabled for improved performance.  
- **Comments Feature**  
  A [PR](https://github.com/rebelonion/Dantotsu/commit/d1e2ca8b5e71cc4e58d3a1201981001cb11fb78a) enables toggleable comments.  
  By default, comments are **off**, so there is no connection to the comments API unless enabled.  

### How to Disable Comments:
1. Visit your [**Anilist settings**](https://anilist.co/settings/apps).  
2. Revoke Dantotsu's access if previously used.  
3. Log in within the app.  

---

## Issues

If you encounter any problems with this build, please [report them here](https://github.com/rebelonion/Dantotsu/).

---

<sub>README.md generated by ChatGPT</sub>
