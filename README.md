# InspBox 3D review viewer

Open the interactive model at **https://dynavect.github.io/inspbox-viewer/**.

Rotate by dragging, zoom with the wheel, and pan with the middle or right mouse
button. Use the component tree to hide parts, or select Open enclosure to see
inside. Reset restores all exported parts, including the door.

This display export includes 212 enclosure components and faceplate lettering.
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
2026-10-17. Source CAD SHA256: 9e4299d6e86615ecef4bd93ef4f3cd52cc0e3841b8c31192f69867658a1b4b52.

INSP and NORM legends now have 3 mm front-view gaps to the guard.

Light rocker now sits left of the inspection selector at the same center height,
with matching ON above and OFF below. All eleven faceplate legends included.
