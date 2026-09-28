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
---

The intention of this project is to create a functional plier design on Fusion, and incorporate multimaterial 3D-printing methods to construct a physical product. These pliers are capable of presisely picking up a through hole resistor, whose diameter measures only about 2.5mm.

# CAD Model

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811ea89f3aa026b5977?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>


# Design Description

The design of these pliers is divided into three distinct sections: the jaws, handles, and flexible portion. The flexible portion, composed of TPU, is an intersection between the handles and jaws which can internally cave in. This allows for the harder parts of the plier to pinch in and out easily. The most important feature of the flexible section is the ability to strongly connect to both the handles and jaws, so that the plier as a whole is one coherent piece that all moves simultaneously. To ensure this cohesion, the perimeter of the flexible portion is drafted with a "dovetail" design. Each side of the square piece has four "dovetails," which are triangular surfaces embedded into the piece, that serve as a jigsaw-like fit between the flexible portion and the handles and jaws, respectively.

The design of both he handles and jaws are relatively simple. The interior of the jaws run parallel to the y-axis to a singular tip at the end, for picking up and moving parts. The outside of the jaws are bulkier on the bottom to give better stability and establish greater surface area with the flexible portion. The handles span diagonally outward to allow for a better grip. 

Both the jaws and handles are made from PLA, a stronger plastic in comparison to PLA. To test appropriate lengths for an ideal model, many dimensions of the project are parameterized, including handle and jaw lengths, flexible portion and dovetail widths, and overall thickness of the plier.

# Print-in-Place Parts

Print‑in‑place parts are 3D‑printed mechanisms designed with built‑in clearance gaps. These allow hinges, joints, and similar connecting interfaces to move in tandem to each other. This plier model is a prime example of the print-in-place method, as two plastic materials with different purposed were incorporated together to create a single product. PLA and TPU tend to work well for print-in-place technology because their typical printing temperatures overlap, and can connect well through interlocking techniques. 

[View the Arduino controller code on GitHub](/Arduino-Code.MD)

# Specifications

| # | Part Name | Quantity |
|---|-----------|----------|
| 1 | Power Cord Hole Plug | 1 |
| 2 | 91290A115 Alloy Steel Socket Head Screw | 8 |
| 3 | Plastic_Body | 1 |
| 4 | Button | 1 |
| 5 | Contact1 | 1 |
| 6 | Metal_Body | 1 |
| 7 | LED 10mm White | 1 |
| 8 | Contact2 | 1 |
| 9 | 91290A222 Alloy Steel Socket Head Screw | 14 |
| 10 | Nut-tr8x8-4 | 1 |
| 11 | Linear-Rod-8mmx200mm | 1 |
| 12 | Rubber Tampon 20ml | 1 |
| 13 | Syringe Cylinder 20ml | 1 |
| 14 | LM8UU Linear Bearing | 1 |
| 15 | Syringe Piston 20ml | 1 |
| 16 | V-Slot 20x40x350 | 1 |
| 17 | 91290A113 Alloy Steel Socket Head Screw | 2 |
| 18 | NEMA-17 Motor | 1 |
| 19 | Lead-Screw-TR8x8x250mm | 1 |
| 20 | M5-Tee-Nut | 13 |
| 21 | Default (1) | 2 |
| 22 | 91390A403 Alloy Steel Cup-Point Set Screw | 2 |
| 23 | 99461A941 Phillips Rounded Head Thread-Forming Screws | 6 |
| 24 | Housing Removable Panel | 1 |
| 25 | LED Hole Plug | 1 |
| 26 | Lead-Screw-SubAssembly | 1 |
| 27 | SWITCH_LIMITE | 1 |
| 28 | Housing | 1 |
| 29 | Housing Cover | 1 |

# 3D Printed Parts

| # | Part Name | Quantity |
|---|-----------|----------|
| 1 | Motor-Mounting-Plate | 1 |
| 2 | Flexible Coupler | 1 |
| 3 | End-Support-Regular | 1 |
| 4 | End-Support - Flange Slots | 1 |
| 5 | Carriage | 1 |
| 6 | End-Support - Holds Syringe Tip | 1 |

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
