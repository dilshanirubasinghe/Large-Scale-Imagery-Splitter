# Drone Imagery Tiling Utility

A Python-based tool for splitting large geospatial drone images (TIFF) into smaller, manageable tiles using `rasterio`. This is particularly useful for preparing datasets for machine learning models or web-based map viewers.

## Features
- Automated tiling of large `.tif` files.
- Handles edge cases where image dimensions aren't perfectly divisible by tile size.
- Preserves geospatial metadata (CRS and Transform) for every tile.

## Setup
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Run the notebook in Google Colab or locally.

## Project Structure
- `notebooks/`: Contains the main Colab processing notebook.
- `Scripts/`: Contains the `tiling_logic.py` script.
- `Examples/`: (Ignored) Default directory for generated tiles.
