# Data Directory

This folder contains processed county-level nighttime-light imagery used for the project:

**Estimating Economic Activity from Nighttime Satellite Imagery**

## Files

### opt1_county_only.zip
- County-level nighttime-light images
- Preserves original county proportions
- County-only extraction
- Grayscale nighttime imagery
- Some files were removed due to GitHub file size limitations

### opt2_county_dark.zip
- Alternative preprocessing version
- Dark background style
- County border included
- Grayscale nighttime imagery

---

## Notes

Because GitHub has repository and upload size limitations, the full processed dataset is not included in this repository.

The uploaded files contain reduced/sample versions of the processed county imagery for demonstration and experimentation purposes.

The complete dataset can be regenerated using the preprocessing pipeline provided in:

```text
src/preprocessing.py
