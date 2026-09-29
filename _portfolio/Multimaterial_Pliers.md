---
title: "Multimaterial Pliers"
excerpt: "These mutlimaterial pliers were 3D printed with both PLA and TPU to create handles and jaws which can flexibly pinch back and forth."
header:
  image: assets/img/Plier_Render.jpg
  teaser: assets/img/Plier_IRL_crop.jpeg

toc: true
toc_label: "Table of Contents"
toc_sticky: true
toc_icon: bars

feature_row:
  - image_path: /assets/img/1eb0a8a4-f6f9-4697-b6a6-7270331bfa4d.jpg
    alt: "Columbia GSAPP Summer Program"
    title: "Columbia GSAPP Summer Program"
    excerpt: "Reimagined Columbia's Business School and Housing through innovative design and experimentation."
  - image_path: /assets/img/51d189eb-0e2f-4748-a632-9fa1ad18262f.png
    alt: "Rock Creek Property Group"
    title: "Rock Creek Property Group"
    excerpt: "Designed and presented a building proposal for a multi-use high rise."
  - image_path: /assets/img/6bf98a82-6028-4241-bd25-b51657dc3693.jpg
    alt: "Sshape Architecture and Interior Design"
    title: "Sshape Architecture and Interior Design"
    excerpt: "Collaborated with contractors, owners, clients, and superintendents, from ideation to post-construction."
---

The intention of this project is to create a functional plier design on Fusion, and incorporate multimaterial 3D-printing methods to construct a physical product. These pliers are capable of presisely picking up a through hole resistor, whose diameter measures only about 2.5mm.

<video autoplay loop muted playsinline style="max-width:100%;">
  <source src="{{ '/assets/img/giphy_pliers.mp4' | relative_url }}" type="video/mp4">
</video>


# CAD Model

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811ea89f3aa026b5977?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>


# Design Description

The design of these pliers is divided into three distinct sections: the jaws, handles, and flexible portion. The flexible portion, composed of TPU, is an intersection between the handles and jaws which can internally cave in. This allows for the harder parts of the plier to pinch in and out easily. The most important feature of the flexible section is the ability to strongly connect to both the handles and jaws, so that the plier as a whole is one coherent piece that all moves simultaneously. To ensure this cohesion, the perimeter of the flexible portion is drafted with a "dovetail" design. Each side of the square piece has four "dovetails," which are triangular surfaces embedded into the piece, that serve as a jigsaw-like fit between the flexible portion and the handles and jaws, respectively.

The design of both he handles and jaws are relatively simple. The interior of the jaws run parallel to the y-axis to a singular tip at the end, for picking up and moving parts. The outside of the jaws are bulkier on the bottom to give better stability and establish greater surface area with the flexible portion. The handles span diagonally outward to allow for a better grip. 

Both the jaws and handles are made from PLA, a stronger plastic in comparison to PLA. To test appropriate lengths for an ideal model, many dimensions of the project are parameterized, including handle and jaw lengths, flexible portion and dovetail widths, and overall thickness of the plier.

# Print-in-Place Parts

Print‑in‑place parts are 3D‑printed mechanisms designed with built‑in clearance gaps. These allow hinges, joints, and similar connecting interfaces to move in tandem to each other. This plier model is a prime example of the print-in-place method, as two plastic materials with different purposed were incorporated together to create a single product. PLA and TPU tend to work well for print-in-place technology because their typical printing temperatures overlap, and can connect well through interlocking techniques. 

As mentioned, [hinges](https://www.howtogeek.com/print-in-place-models-are-the-real-magic-of-3d-printing) are a very practical application of print-in-place parts. This is because by utilizing the print-in-place method, users can bypass an extra assembly step, as the product assembles itself. Chain links, nuts and bolts, and balls and sockets are additional print-in-place options.

# Specifications

| # | Parameter | Length (mm) |
|---|-----------|----------|
| 1 | Flexible Portion Side | 30 |
| 2 | Dovetail Long Side | 5.25 |
| 3 | Dovetail Short Side | 3 |
| 4 | Dovetail to Corner | 3.75 |
| 5 | Jaw Interior Height | 131.25 |
| 6 | Jaw Exterior Height A | 75 |
| 7 | Jaw Exterior Height B | 37.5 |
| 8 | Handle Interior Height A | 63.75 |
| 9 | Handle Interior Height B | 30 |
| 10 | Handle Exterior Height A | 75 |
| 11 | Handle Exterior Height B | 56.25 |
| 12 | Width | 11.25 |

# Print Settings

| Feature | Info |
|---|-----------|
| Perimeters | 0 |
| Top Layers (Flexible Portion) | 0 |
| Bottom Layers (Flexible Portion) | 0 |
| Fill Density (Flexible Portion) | 23% |
| Nozzle | 0.6mm (Blue) |
| Material Used | TPU (Flexible Portion), PLA (Jaws, Handles) |

feature_row:
  - image_path: /assets/img/1eb0a8a4-f6f9-4697-b6a6-7270331bfa4d.jpg
    alt: "Columbia GSAPP Summer Program"
    title: "Columbia GSAPP Summer Program"
    excerpt: "Reimagined Columbia's Business School and Housing through innovative design and experimentation."

  - image_path: /assets/img/51d189eb-0e2f-4748-a632-9fa1ad18262f.png
    alt: "Rock Creek Property Group"
    title: "Rock Creek Property Group"
    excerpt: "Designed and presented a building proposal for a multi-use high rise."

  - image_path: /assets/img/6bf98a82-6028-4241-bd25-b51657dc3693.jpg
    alt: "Sshape Architecture and Interior Design"
    title: "Sshape Architecture and Interior Design"
    excerpt: "Collaborated with contractors, owners, clients, and superintendents, from ideation to post-construction."

<style>
.feature__wrapper .archive__item-teaser {
  height: 220px;
  overflow: hidden;
}

.feature__wrapper .archive__item-teaser img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: center;
}
</style>

{% include feature_row %}
