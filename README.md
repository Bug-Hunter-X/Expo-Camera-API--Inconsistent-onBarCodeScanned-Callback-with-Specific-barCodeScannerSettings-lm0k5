# Expo Camera onBarCodeScanned Inconsistency Bug

This repository demonstrates a bug in Expo's Camera API where the `onBarCodeScanned` prop's callback function doesn't consistently fire when using specific `barCodeScannerSettings`. This is likely due to an edge case in the underlying barcode scanning library, causing issues with certain barcode types, distances, and angles.

The `bug.js` file showcases the problematic code, illustrating the inconsistent callback behavior.  The `bugSolution.js` file demonstrates potential workarounds.  Further investigation and possible solutions may include experimenting with alternative barcode scanning libraries or adjusting scanning parameters.