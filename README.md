# Voices for B2B Exam Prep

The app's own downloadable voices, served from GitHub Pages for https://rabinnapit.github.io/51C. Nothing here is a
program a person runs: the app fetches these files once, keeps them on the device, and speaks lessons offline with them.

| Voice | File | Who | Licence |
|---|---|---|---|
| Amber (US woman) | `v1/en_US-hfc_female-medium.onnx` | Piper voice trained on the HFC dataset | CC BY-NC-SA 4.0 (see MODEL_CARD) |
| Joe (US man) | `v1/en_US-joe-medium.onnx` | Piper voice, OHF-Voice datasets | CC0 |
| Cori (UK woman) | `v1/en_GB-cori-medium.onnx` | Piper voice, LibriVox recordings | Public domain |
| Leo (UK man, northern English) | `v1/en_GB-northern_english_male-medium.onnx` | Piper voice | CC BY-SA 4.0 |

Runtime: [Piper](https://github.com/rhasspy/piper) (MIT), its phonemizer compiled to WebAssembly by
[diffusionstudio/piper-wasm](https://www.npmjs.com/package/@diffusionstudio/piper-wasm) (MIT, with espeak-ng data, GPL-3.0),
and [ONNX Runtime Web](https://onnxruntime.ai/) 1.18.0 (MIT). Each voice's MODEL_CARD is beside its model.

B2B Exam Prep is a free, non-commercial study aid by SFC Rabin Napit.
