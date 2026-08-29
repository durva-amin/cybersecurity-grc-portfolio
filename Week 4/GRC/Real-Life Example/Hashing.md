# Real-Life Example

You download a software file.

The provider publishes its SHA-256 hash.

You calculate the hash of your downloaded file and compare them.

```
Expected Hash = ABC123
Downloaded File Hash = ABC123

MATCH ✅
```

This provides evidence that the file has not changed relative to the published value.

If:

```
Expected = ABC123
Actual   = XYZ789

NOT MATCHING ❌
```

The file may have been modified, corrupted, or may simply not be the expected file.