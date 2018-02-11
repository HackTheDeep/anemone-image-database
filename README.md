The file `image_database.csv` describes the .tif files of anemone nematocysts provided for the challenge. Currently, the database covers only images in the folders (all paths relative to the `HACKATHON` folder found on the "everything" drive):

- `Streamline process/measured`
- `Search engine/test`

For each image, the database currently contains:

- *path* The path to the .tif file, relative the `HACKATHON` folder provided for the challenge. You'll likely recognize the address of images your working.
- *taxa* The genus and/or species of the pictured nematocyst.
- *specimen* The specimen identifier
- *tissue* The tissue type of the image
- Paths for the metadata files. Note these are **nontrivial** and not merely produced by appending the respective extension!
  - *path_anx* Path to the .anx file, if it exists. If not, an empty string.
  - *path_cal_xml* Path to the .cal.xml file, if it exists. If not, an empty string.
  - *path_eax* Path to the .eax file, if it exists. If not, an empty string.
  - *path_lmd* Path to the .lmd file, if it exists. If not, an empty string.
  - *path_sbx* Path to the .sbx file, if it exists. If not, an empty string.
- *canonical_name* The taxa, specimen, tissue and an image identifier concatenated with underscores. Useful for image files names.
# TODO
- Add length and width for measured files
- What do you need???
