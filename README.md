# PCD_Assignment02

This repository contains my second Digital Image Processing assignment about image enhancement.

In this assignment, I worked with four different image problems: **blur, excessive brightness, darkness, and low contrast**. Each problem uses one image and one enhancement method. The results are compared visually and using **PSNR (Peak Signal-to-Noise Ratio)** before and after enhancement.

## Image Problems and Methods

| Problem | Enhancement Method |
|---|---|
| Blur | Sharpening Filter |
| Bright Image | Gamma Correction |
| Dark Image | Logarithmic Transformation |
| Low-Contrast Image | Contrast Stretching |

## PSNR Results

| Problem | Before Enhancement | After Enhancement | Improvement |
|---|---:|---:|---:|
| Blur | 26.88 dB | 27.89 dB | +1.01 dB |
| Bright | 16.13 dB | 23.51 dB | +7.38 dB |
| Dark | 11.63 dB | 13.97 dB | +2.34 dB |
| Low Contrast | 19.09 dB | 50.86 dB | +31.77 dB |
| **Average** | **18.43 dB** | **29.06 dB** | **+10.62 dB** |

All four cases showed an increase in PSNR after enhancement. In this experiment, the low-contrast case showed the largest PSNR improvement after Contrast Stretching was applied.

## Folder Structure

```text
PCD_Assignment02/
├── PCD_Assignment02.ipynb
├── images/
│   ├── original/
│   │   ├── original_blur.JPG
│   │   ├── original_bright.JPG
│   │   ├── original_dark.JPG
│   │   └── original_low_contrast.JPG
│   ├── degraded/
│   │   ├── blurred.JPG
│   │   ├── bright.JPG
│   │   ├── dark.JPG
│   │   └── low_contrast.JPG
│   └── enhanced/
│       ├── sharpened.JPG
│       ├── gamma_corrected.JPG
│       ├── log_transformed.JPG
│       └── contrast_stretched.JPG
├── report/
│   └── PCD_Assignment02_Report.pdf
└── README.md
```

## Notebook

The full implementation, visual comparisons, PSNR calculations, analysis, and conclusion are available in:

`PCD_Assignment02.ipynb`

