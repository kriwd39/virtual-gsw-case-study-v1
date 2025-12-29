# Forensic Case Report: Gunshot Wound Analysis
## Case ID: GSW-2023-001
## Date of Report: 2025-12-28
## Analyst: Dr. Jane Doe, Forensic Pathologist
## Imaging Modality: Post-mortem CT (PMCT)

### 1. Executive Summary
A post-mortem CT examination was performed on an adult male decedent with a single gunshot wound to the left thorax. The imaging revealed a retained bullet in the posterior thoracic soft tissues, multiple metallic fragments along the wound track, a comminuted fracture of the left 6th rib, and subcutaneous emphysema tracking along the bullet path. The trajectory was anterior-to-posterior, slightly superior-to-inferior, and left-to-right. No evidence of gas embolism was identified. This report details the imaging findings and integrates them into a 3D reconstruction and 4D animation for educational purposes.

### 2. Imaging Protocol
- **Scanner**: 64-slice multidetector CT
- **Slice thickness**: 0.625 mm
- **Reconstruction kernel**: bone and soft tissue
- **Contrast**: None (non‑contrast PMCT)
- **Dataset**: Fully anonymized DICOM series (available in `/raw_data`)

### 3. Key Findings

#### 3.1 Radiopaque Foreign Bodies (Issue #1)
- **Retained bullet**: A single deformed metallic projectile (approx. 9 mm diameter) located in the posterior thoracic soft tissues at the level of T7, 2 cm right of midline.
- **Metallic fragments**: Seven small (<3 mm) metallic fragments distributed along the wound track, concentrated near the rib fracture site.
- **Differentiation**: All fragments exhibit typical bullet‑alloy density (~3000 HU). No other foreign bodies (e.g., medical devices) are present.

#### 3.2 Bullet Trajectory and Wound Path (Issue #2)
- **Entry wound**: Cutaneous defect over left anterolateral chest at the 6th intercostal space, with inward beveling of the left 6th rib.
- **Exit wound**: None (bullet retained).
- **Trajectory**: 
  - **Direction**: Anterior → posterior, slightly superior → inferior, left → right.
  - **Angle**: Approx. 15° caudal, 10° medial relative to the axial plane.
- **Structures traversed**:
  1. Skin and subcutaneous tissue
  2. Pectoralis major muscle
  3. Left 6th rib (comminuted fracture)
  4. Visceral pleura
  5. Left lower lobe lung parenchyma (through-and-through)
  6. Posterior thoracic soft tissues (bullet final position)

#### 3.3 Fracture Patterns (Issue #3)
- **Left 6th rib**: Comminuted fracture with inward beveling at the entry site, consistent with a typical ballistic fracture.
- **3D model**: A segmented STL model of the fractured rib is available in `/3d_models/rib_fracture.stl`. The model highlights the radiating fracture lines and the conical defect at the entry site.

#### 3.4 Subcutaneous Emphysema and Gas Embolism (Issue #4)
- **Subcutaneous emphysema**: Present along the bullet track in the left chest wall, extending into the anterior mediastinum. No pneumothorax identified.
- **Gas embolism**: No evidence of intra‑vascular gas on lung‑window or mediastinal‑window images.
- **Significance**: The emphysema likely results from air sucked into the wound channel during the shooting event; it does not indicate a lethal air embolism.

#### 3.5 4D/5D Animation (Issue #5)
- **Software**: OsiriX 3D module and Blender were used to create a time‑resolved animation of the bullet’s path.
- **Animation content**:
  1. Fly‑through of the external anatomy showing the entry site.
  2. Sequential reveal of the wound channel through skin, muscle, rib, lung, and final resting place of the bullet.
  3. Highlight of fracture fragments and metallic debris.
- **Output**: The animation is saved as `/animations/trajectory_animation.mp4`. A simplified 3D PDF is also provided (`/animations/trajectory_3d.pdf`).

### 4. Integration of Findings
The imaging findings are consistent with a single, intermediate‑range gunshot wound to the left chest. The bullet entered the left anterolateral chest, fractured the 6th rib, traversed the left lower lobe, and came to rest in the posterior soft tissues. The absence of an exit wound, the retained bullet, and the subcutaneous emphysema are typical for a low‑velocity projectile. The fracture pattern and fragment distribution support a perpendicular-to‑slightly‑angled entry.

### 5. Limitations
- **PMCT vs. autopsy**: CT cannot assess soft‑tissue hemorrhages, organ lacerations, or microscopic findings as reliably as conventional autopsy.
- **Metal artifacts**: Beam‑hardening artifacts around the bullet slightly obscure adjacent soft‑tissue details.
- **Anonymization**: The dataset lacks patient demographic and circumstantial information, limiting correlation with scene findings.

### 6. Conclusion
Post‑mortem CT provided a non‑invasive, detailed visualization of the gunshot wound anatomy, foreign bodies, fracture, and air distribution. The integration of 3D models and 4D animation enhances the educational value of the case, allowing trainees to appreciate the spatial relationships and dynamic nature of ballistic injuries. This case underscores the utility of PMCT as an adjunct to traditional autopsy in forensic investigations.

### 7. References
1. Thali MJ, et al. *Virtopsy, a new imaging horizon in forensic pathology*. Forensic Sci Int. 2003.
2. Levy AD, et al. *Postmortem CT in gunshot wound victims*. Radiol Clin North Am. 2015.
3. OsiriX Imaging Software – User Guide.

### 8. Appendices
- **Appendix A**: Screenshots of key CT slices (stored in `/analysis_notes/screenshots/`).
- **Appendix B**: Segmentation parameters used for 3D model generation.
- **Appendix C**: Animation storyboard and keyframe descriptions.

---
*This report is part of the educational module `virtual-gsw-case-study-v1`. All data are anonymized and intended solely for teaching purposes.*