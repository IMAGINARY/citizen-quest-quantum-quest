# Quantum Quest art workflow

## Photoshop

The original art is in `background.psb`. 

- Layer > Flatten image
- Image > Mode > RGB Color
- Image > Image Size... 
  - 6265 x 1080
  - Resample: Preserve Details 2.0
- File > Export > Export As...
  - Format: PNG
  - No resizing
  - Filename: `background-resized.png`

Then open all the scenery files:

- bank-grass-left.psd
- bank-grass-right.psd
- cafe-bag.psd
- cafe-counter.psd
- cafe-table-01.psd
- cafe-table-02.psd
- forest-big-mushrooms.psb
- forest-medium-mushrooms.psd
- forest-small-mushroom.psd
- forest-tiny-mushroom.psd
- post-office.psd

For each file do the following:

- Image > Mode > RGB Color
  - Don't merge
- Image > Image Size...
  - 17.45% of original size
  - Resample: Preserve Details 2.0
- File > Export > Quick export as PNG
  - Filename: 'scenery/<name>'

They need to be reduced by the same proportion as the background image (34.9%) and exported to 
PNG format.
