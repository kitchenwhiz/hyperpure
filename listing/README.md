# Listing

Finalised marketplace listings, grouped by brand. Each brand folder holds one consolidated Excel file and an `images/` folder.

```
listing/
  USP/                      All USP products (USP Essentials, USP Ecoline)
    USP_Listings.xlsx       Summary sheet + one sheet per product
    images/
      01_SS_GT_35L_GT53H3/
        01_SS_GT_35L_GT53H3_image_1.jpg
        ...
```

## Conventions

- **S.No** runs across the whole brand file and never restarts. The Summary sheet groups products by listing set (Set 1, Set 2, ...). Each new finalised set is added at the end with the next S.No values.
- **Image folders** are named `<S.No>_<short name>`. Each image inside is named `<S.No>_<short name>_image_<n>.jpg`. All images are 500 x 500 px JPG.
- **Short names** keep paths short: SS = stainless steel, MS = mild steel, GT = grease trap, DG = drain grating, WT = work table, CS = cross support, US1 / US2 = 1 or 2 under shelves, OHS2 = 2 overhead shelves, BS = back splash, 5TR = 5 tier rack. Numbers are length in mm (or litres for grease traps), followed by the EQ code.
- **Prices** are in Rs, excluding GST (18%), shipping, unloading and installation. The Price basis column says where each price came from.

## Sets in USP_Listings.xlsx

| Set | S.No | Products |
|---|---|---|
| Set 1 | 1-10 | Grease traps (35 / 60 / 85 L), drain gratings (300 / 600), work table 1050 with 2 under shelves, SS 5 tier racks (900 / 1150), MS 5 tier racks (900 / 1200) |
| Set 2 | 11-22 | Work tables with 2 overhead shelves and back splash: cross support, 1 under shelf, 2 under shelves (900 / 1150 / 1500 each); 2 tier overhead shelves (900 / 1150 / 1500) |
