# On-device text reading (OCR)

Served from our own site so images never leave the device and no outside
service is used. Files and sources (all Apache-2.0):

- `tesseract.min.js`, `worker.min.js`: npm `tesseract.js` 5.1.1 (`dist/`)
- `tesseract-core-lstm.wasm.js`, `tesseract-core-simd-lstm.wasm.js`: npm `tesseract.js-core` 5.1.1
- `heb.traineddata.gz`, `eng.traineddata.gz`: npm `@tesseract.js-data/heb` and `/eng` 1.0.0, folder `4.0.0_best_int`

To update: bump `tesseract.js` (devDependency) and copy the files again.
