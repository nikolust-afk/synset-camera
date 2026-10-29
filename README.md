# Synset Camera

A full-screen camera that boxes every face and labels it with one of ImageNet-21k's
2,834 "person" categories (the fall 2011 release) and that category's definition.
Part of a thesis on how datasets classify people with nouns.

- Everything runs in the browser (onnxruntime-web). Nothing is uploaded.
- Faces: UltraFace RFB-320. Labels: ViT-S/16 trained on ImageNet-21k, output cut to the person subtree, 8-bit.
- Captures are kept in the browser's storage on the device; "Export archive" saves them as a zip.

The labels are ImageNet's own, including offensive ones. That is the subject of the work.
