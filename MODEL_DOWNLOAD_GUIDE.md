# 3D Model Download Guide for Edith Finch-Style Room

Download these free 3D models to replace the procedural geometry with realistic assets.

## Quick Start

1. Create a free [Sketchfab account](https://sketchfab.com/signup)
2. Download each model in **GLTF/GLB** format
3. Rename files to match the expected filenames
4. Place in `assets/models/` folder
5. Refresh the page - models auto-load!

---

## Required Models

### Priority 1: Main Furniture

| Item | Expected Filename | Download Link | License |
|------|-------------------|---------------|---------|
| Bookshelf | `bookshelf.glb` | [CC0 Bookshelf with Books](https://sketchfab.com/3d-models/cc0-bookshelf-with-books-961af2daa6344e4fba0c7a4c92ff91f8) | CC0 |
| Desk | `desk.glb` | [Victorian Desk](https://sketchfab.com/3d-models/victorian-desk-ac061b3de2b9480d8ca175e9fdc0c785) | Free |
| Armchair + Table + Lamp | `armchair.glb` | [Leather Armchair/Coffee Table/Floor Lamp](https://sketchfab.com/variandev/collections/antique-69793c77765148bda1aa632929fb2320) | Free |
| Grandfather Clock | `grandfather_clock.glb` | [Vintage Grandfather Clock](https://sketchfab.com/3d-models/vintage-grandfather-clock-a0736779404a4a6b94e61dbaa500651d) | Free |
| Gramophone | `gramophone.glb` | [Vintage Gramophone](https://sketchfab.com/3d-models/vintage-gramophone-game-asset-by-rigdhi) | Free |
| Side Table | `side_table.glb` | [Antique Table](https://sketchfab.com/3d-models/antique-table-6b5c4d3e2f1a4b5c6d7e8f9a0b1c2d3e) | Free |

**Note:** The `armchair.glb` model includes a leather armchair, coffee table, AND floor lamp all in one file. No separate floor lamp needed!

### Priority 2: Decorative Items

| Item | Expected Filename | Download Link | License |
|------|-------------------|---------------|---------|
| Typewriter | `typewriter.glb` | [Vintage Typewriter](https://sketchfab.com/3d-models/typewriter-0b6766c2df0e4901b8c387283d544027) | Free |
| Radio | `radio.glb` | [Vintage Radio](https://sketchfab.com/3d-models/vintage-radio-d7d924cb3d1f4b229e2aa62dcee77fd3) | Free |
| Globe | `globe.glb` | Search "vintage globe" on Sketchfab | Varies |
| Telephone | `telephone.glb` | Search "rotary telephone vintage" on Sketchfab | Varies |
| Mirror | `mirror.glb` | [Ornate Mirror](https://sketchfab.com/3d-models/ornate-mirror-xyz) | Free |
| Suitcase | `suitcase.glb` | [Vintage Suitcase](https://sketchfab.com/3d-models/vintage-suitcase-c5cddbff1b26435db917a21e450924ec) | Free |

---

## Alternative Sources (CC0)

### Poly Haven
- [polyhaven.com/models](https://polyhaven.com/models) - All CC0, direct GLTF downloads

### Quaternius
- [quaternius.com](https://quaternius.com) - Low-poly furniture packs, CC0

### Kenney
- [kenney.nl/assets](https://kenney.nl/assets) - Stylized furniture, CC0

---

## Sketchfab Collections (Curated Free Models)

1. **[Victorian and Vintage Furniture](https://sketchfab.com/apatel/collections/dl-victorian-and-vintage-furniture-85abfb5d444e48aeb3e472db46502b4b)** by Antoine Patel

2. **[Antique Collection](https://sketchfab.com/variandev/collections/antique-69793c77765148bda1aa632929fb2320)** by VarianDev
   - Includes: Leather armchair, coffee table, floor lamp (all in one!), antique desk, bookshelf, chandelier, wardrobe

---

## How to Download from Sketchfab

1. Click the model link
2. Click **"Download 3D Model"** button
3. Select **"glTF"** format
4. Extract the ZIP file
5. Find the `.glb` or `.gltf` file
6. Rename to match expected filename
7. Copy to `assets/models/` folder

---

## Adjusting Model Scale/Position

Edit `MODEL_CONFIG` in `room.html`:

```javascript
const MODEL_CONFIG = {
    bookshelf: {
        file: 'bookshelf.glb',
        position: [-3.5, 0, -2.5],
        rotation: [0, Math.PI/2, 0],
        scale: 1  // or [1, 1, 1] for non-uniform
    },
    // ...
};
```
