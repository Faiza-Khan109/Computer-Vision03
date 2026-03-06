# Image Enhancement for Computer Vision Applications

This repository contains Python implementations of several **image enhancement techniques** used in computer vision.

These techniques improve image quality under challenging environmental conditions.

---

# Enhancement Methods

## Contrast Stretching
Expands the dynamic range of pixel intensities.

Formula:

I_new = ((I - I_min)/(I_max - I_min)) * 255

---

## Gamma Transformation
A nonlinear transformation used to control brightness.

Formula:

I_out = 255 * (I_in/255)^gamma

---

## Histogram Equalization
Redistributes pixel intensity values to improve global contrast.

---

## CLAHE
Contrast Limited Adaptive Histogram Equalization enhances **local contrast** while preventing noise amplification.

---

# Images Used in the Project

- X-ray medical images
- Low-light surveillance images
- Foggy traffic scenes
- Satellite thermal images
- Underwater photographs

---

# Real-World Applications

| Application | Technique Used |
|-------------|---------------|
| Marine Biology | Histogram Equalization + Gamma |
| Autonomous Vehicles | CLAHE |
| Security Surveillance | Contrast Stretching + Gamma |
| Traffic Monitoring | Contrast Stretching + Histogram Equalization |
| Environmental Monitoring | Gamma + Histogram Equalization |

---

# Output

Each script displays:

- Original Image
- Enhanced Image
- Histogram Analysis (where applicable)

Visualization is performed using **Matplotlib**.
