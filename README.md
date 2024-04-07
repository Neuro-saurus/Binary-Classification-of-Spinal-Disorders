# Biomedical Dataset Overview

This dataset was curated by **Dr. Henrique da Mota** during his medical residency in **Lyon, France**. It aims to represent each patient with a comprehensive set of biomechanical attributes that reflect the shape and orientation of the pelvis and lumbar spine. These attributes are critical in the diagnosis and understanding of various spinal conditions.

## Dataset Attributes

Patients are characterized by the following six biomechanical attributes:

- **Pelvic Incidence**: A numerical value indicating the angle of the pelvis.
- **Pelvic Tilt**: The tilt of the pelvis measured in degrees.
- **Lumbar Lordosis Angle**: The curvature angle of the lumbar spine.
- **Sacral Slope**: The slope of the sacral region of the spine.
- **Pelvic Radius**: A measure of the pelvic cavity's radius.
- **Grade of Spondylolisthesis**: The severity of spondylolisthesis present.

## Classification Labels

The dataset categorizes patients into four distinct classes based on their spinal conditions:

- **Disk Hernia (DH)**
- **Spondylolisthesis (SL)**
- **Normal (NO)**
- **Abnormal (AB)**

For this analysis, we focus on a binary classification task. The labels are simplified as follows:

- **Normal (NO)**: Represented as `0`
- **Abnormal (AB)**: Represented as `1`
