Library model photos for the realistic pictures: 34 invented people from src/data.js CAST (28 adults, 6 children).
Two photos per person: <id>.jpg (full length, facing the camera, plain light studio background, simple fitted
neutral clothing) and <id>-face.jpg (head-and-shoulders portrait of exactly the same person).
For the runway each person also has <id>-cut.png and <id>-three-cut.png (the person cut out of the studio photo, front and
quarter turn) and one list, cutouts.json. Make them with:  python3 scripts/cutout.py --models public/models --weights <isnet-general-use.onnx>
(and again with --suffix=-three). Look at every cut-out, especially the shoes.
Made by Pink with: node scripts/make-models.mjs --dry, then without --dry, or by the founder by hand
(docs/make-assets-guide.md) and added with scripts/add-assets.mjs.
Never a photo of a real or famous person. The app only shows the photos that exist.
