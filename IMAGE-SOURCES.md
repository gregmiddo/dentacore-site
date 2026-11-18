# Where the website's X-ray pictures come from

Swap any of these out if the rights to an image are ever in doubt. All came from two grids Greg
uploaded on 14 Nov 2026 and look web-sourced.

## Grid 2 ("try these": bitewings, periapicals, panos)
Numbered left to right, top to bottom from 0; the bottom row is 15a to 15e.
- `img/bitewing-a.webp` grid 2 #3 · `bitewing-b` #4 · `bitewing-c` #9 · `bitewing-d` #12 · `bitewing-e` #15a · `bitewing-f` #15c
- `img/bitewing-ortho-1.webp` #0 · `bitewing-ortho-2` #1 (brackets; corner marks cropped off)
- `img/periapical-a.webp` #5 · `periapical-b` #7 · `periapical-c` #14 · `periapical-d` #15e
- `img/pano-a.webp` #6 (R mark and black bars cropped) · `pano-b` #8 · `pano-c` #11 · `pano-d` #13 (R/L cropped) · `pano-e` #15b · `pano-f` #15d
- Left out: #2 (photographed, finger in shot), #10 (photographed on a lightbox).

## Grid 1 (16 panoramic X-rays)
Numbered left to right, top to bottom from 0.
- `img/pano-14.webp`, `img/pano-15.webp`: whole panos 14 and 15, R mark trimmed.
- Left out: #8 (NewTom mark and scale bar), #7 (R/L marks inside the picture).

## Composited into DentaCore screenshots
- `img/mainwindow_imaging.webp`: gallery row 1 = bitewing-a, bitewing-e, bitewing-d, bitewing-b;
  row 2 tiles 4 and 5 = bitewing-ortho-1, periapical-c; row 2 tile 3 = DentaCore's demo profile photo (synthetic).
  The smile photo, the FMX tile and the panoramic tile were already in the original screenshot.
- `img/image_viewer_dialog.webp`: main picture bitewing-e; filmstrip bitewing-e, bitewing-a, periapical-b, pano-c.
- `img/compare_images_dialog.webp`: DentaCore's own demo ceph (synthetic), both sides.

## Pages that show the X-rays directly
- Imaging page, "Radiographs" section: the bitewing, periapical and panoramic strips.
- Overview page, Coming soon: bitewing tools.

Everything else (ceph, CBCT, every other screen) is an unchanged screenshot from the DentaCore Guide.
The fake-looking ones (the synthetic CBCT ring, the 3D torus model, placeholder intraoral photos) aren't used.

## Added in the one-screen redesign (14 Nov 2026)

- `study_mount_sample`: a layout of bitewing-a, bitewing-e and periapical-a to d from the grid above, on a dark background. Used for Study mounts.
- Single X-rays are also used on their own screens: pano-a (Adding images), bitewing-c (Capture sequences), pano-d (Timepoints), bitewing-f (Hot folder), pano-f (PACS), bitewing-d (Coming soon), and on the home page: bitewing-e, pano-c.
- `cbct_slices_crop` and `dash_header_crop` are crops of DentaCore screenshots (the CBCT measuring window and the Dashboard header).

## Practice photos (Unsplash License, free for commercial use, no attribution required)

Downloaded 14 Nov 2026 from images.unsplash.com and cropped to 3:2. Credited here as a courtesy.

| File | Photo page | Photographer | Used on |
|---|---|---|---|
| photo-talk | https://unsplash.com/photos/dentist-talking-to-patient-in-a-modern-dental-office-Bg81yWKZlMg | Harold Hisona | Home, Book a demo |
| photo-scanner | https://unsplash.com/photos/dentist-examining-patient-with-dental-scanner-joILn6p_oeM | Filip Rankovic Grobgaard | Home, CBCT · Intraoral scans and models |
| photo-office | https://unsplash.com/photos/modern-dental-office-with-chair-and-equipment-e7MJLM5VGjY | Benyamin Bohlouli | Why DentaCore · How it runs |
| photo-manexam | https://unsplash.com/photos/dentist-examining-teeth-in-dental-office-BiknMFl7iOw | D Dental Office | Why DentaCore · Roles |
| photo-tablet | https://unsplash.com/photos/dentist-pointing-at-dental-scan-VckdJzo7ig0 | Quang Tri NGUYEN | Imaging · Adding images |
| photo-working | https://unsplash.com/photos/a-dentist-working-on-a-patient-AWqHc49SU-c | Ozkan Guner | Imaging · Capture sequences |
| photo-chairwhite | https://unsplash.com/photos/a-white-dental-chair-in-a-room-with-a-window-44jaETSVX2I | Katarzyna Zygnerska | Imaging · Hot folder |
| photo-chairorange | https://unsplash.com/photos/dental-chair-in-clinical-office-XJptUS8nbhs | Atikah Akhtar | Appointments · Rooms |
| photo-womancheck | https://unsplash.com/photos/a-woman-getting-her-teeth-checked-by-a-dentist-z8BIWPwV3zo | SoyBreno | Clinical · Chairside |
| photo-toothmodel | https://unsplash.com/photos/dentist-showing-a-model-of-a-damaged-tooth-SU6EGDd-ySQ | Harold Hisona | Clinical · Case acceptance |
| photo-smile | https://unsplash.com/photos/a-close-up-of-a-womans-mouth-with-white-teeth-RCQnbyQsnUg | Kamal Hoseinianzade | Communications · Reminders |
| photo-braces | https://unsplash.com/photos/dental-model-with-metal-braces-on-teeth-cx3JCL5PDew | Harold Hisona | Orthodontics · Contracts |

X-rays removed in this round: the radiograph grid went from 12 to 4 (bitewing-e, bitewing-ortho-1, periapical-b, pano-c), and pano-a, bitewing-c, bitewing-f and pano-f were replaced by photos or screenshots. pano-d remains on Capture timepoints, and bitewing-d on Coming soon.

## Frontal (PA) ceph (third-party, CC BY 4.0)

`ceph_ricketts_frontal_real` and `ceph_grummons_results_real` use a real posteroanterior cephalogram: panel (c), "man without scoliosis", of Figure 1 in:

> "Association between idiopathic scoliosis and facial asymmetry: a gender-balanced case-control study." *Scientific Reports* (2026). doi:10.1038/s41598-026-36422-4 (PMC12917111). Licensed under Creative Commons Attribution 4.0 International, https://creativecommons.org/licenses/by/4.0/

Changes made: cropped to the one panel, the authors' coloured reference lines removed (digitally filled in), converted to greyscale and enlarged. DentaCore's Ricketts frontal and Grummons landmarks and lines were then drawn over it and placed in the Ceph Analysis window. The landmark positions were placed by eye for illustration. They are not a clinical tracing.

Attribution required by the licence: credit the article and authors as above, link the licence, and say that changes were made. The site shows this in the picture's caption and in this file.

## Orthodontic photos (Unsplash License), added 15 Nov 2026

| File | Photo page | Photographer | Used on |
|---|---|---|---|
| photo-bracesportrait | https://unsplash.com/photos/a-woman-smiling-for-the-camera-kzJL-luv594 | Katarzyna Zygnerska | Home (orthodontist), Your orthodontic office, Active treatment |
| photo-alignerfit | https://unsplash.com/photos/woman-adjusting-clear-dental-aligners-on-teeth-uTUsnv_UCSQ | Harold Hisona | Home (orthodontist), Active treatment |
| photo-aligner | https://unsplash.com/photos/person-inserting-clear-dental-aligner-fmB7IdFjhTM | Diana Polekhina | Records & imaging |
| photo-adjust | https://unsplash.com/photos/person-with-silver-teeth-braces-hKaYlAF1nDw | Atikah Akhtar | Records & imaging, Active treatment |
| photo-bracesmile | https://unsplash.com/photos/close-up-of-a-persons-mouth-YKqYvUYzw0w | Ozkan Guner | Families & referrers |
| photo-models | https://unsplash.com/photos/a-close-up-of-a-tooth-with-braces-on-it-P8ernb_Ht-M | Katarzyna Zygnerska | Records & imaging |
| photo-alignermodel | https://unsplash.com/photos/a-model-of-a-teeth-with-braces-and-braces-B9lLokDYTMY | Katarzyna Zygnerska | New patients & consultations |
