# InspBox 3D review viewer

Open the interactive model at **https://dynavect.github.io/inspbox-viewer/**.

Rotate by dragging, zoom with the wheel, and pan with the middle or right mouse
button. Use the component tree to hide parts, or select Open enclosure to see
inside. Reset restores all exported parts, including the door.

This display export includes 211 enclosure components and faceplate lettering.
The PCB, attached display and board connectors are excluded. The ruler reports
millimetres; the Details panel reports model dimensions in metres. Explode is
illustrative, and section views do not add solid cut faces. Use approved CAD and
manufacturing documents for fabrication, not measurements from this review mesh.

The model is approximately 55 MB. Allow time for the initial download and outline
generation. A desktop browser with WebGL is recommended.

Viewer software: [Online 3D Viewer 0.18.0](https://github.com/kovacsv/Online3DViewer),
with local controls and branding. Third-party licenses and asset attribution
are included under `licenses/` and the relevant asset directories. Those licenses
apply to the software/assets; they do not grant a license to manufacture the
enclosure design. This repository contains the public review website only.

Model revision: narrow 40 x 32 mm INSP/NORM guard with an 18.5 mm round opening and 35.2 mm upper button pitch,
2026-10-23. Source CAD SHA256: 7111cc586b61525c60f1672a8c12a905b214def62afbee8e4f7d7eb986e7c42a.

INSP and NORM legends now have 3 mm front-view gaps to the guard.

Light rocker now sits left of the inspection selector at the same center height,
with matching ON above and OFF below. All eleven faceplate legends included.

The three upper faceplate cutouts now align with the DOWN / ENABLE / UP housings,
with opening sizes and switch/guard placements unchanged. Matching manufacturing revision: J.

Light rocker replaced by the complete McMaster-Carr 7395K37 model with its matching
11.1125 x 30.95625 mm panel cutout. ON/OFF legends and other controls retained.
