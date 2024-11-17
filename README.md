## README

### Overview

This project processes and analyzes Autonomous System (AS) classification data from various text files. The data includes information about AS types, sources, and other relevant details.

Project Structure

```
README.md
src/
txt_files/
    20150801.as2types.txt
    20210401.as2types.txt
    20241001.as-org2info.txt
    20241101.as-rel2.txt
    routeviews-rv2-20241106-1400.pfx2as.txt
```    
`txt_files`

This directory contains the raw data files used for the analysis. Each file follows a specific format and contains information about AS classifications, relationships, and other metadata.

- `20150801.as2types.txt`: Contains AS type information as of August 1, 2015.
- `20210401.as2types.txt`: Contains AS type information as of April 1, 2021.
- `20241001.as-org2info.txt`: Contains AS organization information as of October 1, 2024.
- `20241101.as-rel2.txt`: Contains AS relationship information as of November 1, 2024.
- `routeviews-rv2-20241106-1400.pfx2as.txt`: Contains prefix to AS mappings as of November 6, 2024.

### File Format

`20150801.as2types.txt`

- Format: as|source|type
- Metadata:
- date: 20150802
- name: as2type
- exe: type-convert-amogh.pl
- files: /project/as2org/20150801/asclass/exp-sets/20150801.merged.class.txt
- types: Content|Enterpise|Transit/Access

### Example Data

```
1|peerDB_class|Transit/Access
2|CAIDA_class|Transit/Access
3|CAIDA_class|Transit/Access
...
```

## How to Run

1. Clone the repository.
2. Navigate to the project directory.
3. Run the necessary scripts located in the src directory to process the data files in txt_files.