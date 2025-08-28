# Feedback Files and Images Naming Convention

This directory contains user feedback files and associated images with a consistent naming convention.

## Naming Convention

All feedback-related files use the following pattern:
```
feedback_YYYYMMDD_HHMMSS_[feedback_id]
```

Where:
- `YYYYMMDD`: Date in format (e.g., 20250823)
- `HHMMSS`: Time in format (e.g., 143022)
- `feedback_id`: 8-character unique ID (e.g., 28bdcb42)

## File Types

### JSON Feedback Files
- **Format**: `feedback_YYYYMMDD_HHMMSS_[feedback_id].json`
- **Example**: `feedback_20250823_143022_28bdcb42.json`
- **Contains**: Feedback text, metadata, and image references

### Image Files
- **Format**: `feedback_YYYYMMDD_HHMMSS_[feedback_id]_img_[N].ext`
- **Example**: `feedback_20250823_143022_28bdcb42_img_1.jpg`
- **Where**: `[N]` is the image number (1, 2, 3...) and `ext` is the original file extension

## User Association

Files from the same user session share the same base name:
- `feedback_20250823_143022_28bdcb42.json` (feedback text)
- `feedback_20250823_143022_28bdcb42_img_1.jpg` (first image)
- `feedback_20250823_143022_28bdcb42_img_2.png` (second image)

This makes it easy to identify which images belong to which feedback entry.
