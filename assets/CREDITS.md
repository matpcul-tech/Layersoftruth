# Asset credits and licenses

Every third-party asset in this project is either MIT (Microsoft Rocketbox) or CC0 (Poly Haven).
Licenses were checked on the source pages on 2026-10-04.

## Characters: Microsoft Rocketbox Avatar Library (MIT)

Source: https://github.com/microsoft/Microsoft-Rocketbox
License: MIT, Copyright (c) 2020 Microsoft. Full text: https://github.com/microsoft/Microsoft-Rocketbox/blob/master/LICENSE.md
(shipped with the build as `public/assets/ROCKETBOX-LICENSE.txt`).
Original avatars by Rocketbox (Markus Wojcik and team). Facial blendshapes (15 visemes, ARKit set)
by Matias Volonte and Fang Ma. Paper: Gonzalez-Franco et al., "The Rocketbox library and the
utility of freely available rigged avatars", Frontiers in Virtual Reality, 2020, DOI 10.3389/frvir.2020.561558.

| Role | Rocketbox avatar | Source file | Changes |
|---|---|---|---|
| Marcus | Business_Male_06 | Assets/Avatars/Professions/Business_Male_06/Export/Business_Male_06_facial.fbx | FBX to GLB, textures resized and WebP, shirt recolored slate blue-grey |
| Vera | Business_Female_01 | Assets/Avatars/Professions/Business_Female_01/Export/Business_Female_01_facial.fbx | FBX to GLB, suit recolored navy |
| Sarah | Female_Adult_09 | Assets/Avatars/Adults/Female_Adult_09/Export/Female_Adult_09_facial.fbx | FBX to GLB, cardigan recolored olive |
| The Assessor | Business_Female_04 | Assets/Avatars/Professions/Business_Female_04/Export/Business_Female_04_facial.fbx | FBX to GLB |
| David | Male_Adult_14 | Assets/Avatars/Adults/Male_Adult_14/Export/Male_Adult_14_facial.fbx | FBX to GLB |
| The Stranger | Male_Adult_18 |
| Mrs. Chen | Female_Adult_02 | Assets/Avatars/Adults/Female_Adult_02/Export/Female_Adult_02_facial.fbx | FBX to GLB | Assets/Avatars/Adults/Male_Adult_18/Export/Male_Adult_18_facial.fbx | FBX to GLB |

All characters keep the 52 ARKit (AK_*) and 15 viseme (AA_VI_*) blendshapes; the other FACS sets were dropped for size.

### Animations (MIT, same repository)
Source folder: https://github.com/microsoft/Microsoft-Rocketbox/tree/master/Assets/Animations/all_animations_max_motextr_static
Retargeted (baked world-space) onto Business_Male_06 (male library) and Female_Adult_09 (female library), capped at 20 s.
- Male (`public/assets/anims/male.glb`): m_idle_neutral_01, m_gestic_talk_neutral_01, m_gestic_talk_neutral_02, m_gestic_listen_neutral_01,
  m_sit_table_idle_neutral_01, m_sit_table_breathe_01, m_sit_table_gestic_thoughtful, m_sit_table_gestic_shrug_01, m_sit_table_idle_nervous_01
- Female (`public/assets/anims/female.glb`): f_idle_neutral_01, f_gestic_talk_neutral_01, f_sit_table_idle_neutral_01, f_sit_table_breathe_01,
  f_sit_table_gestic_thoughtful, f_sit_table_gestic_shrug_01, f_sit_table_idle_touch_hair

## Props, surface textures, HDRIs: Poly Haven (CC0)

License: CC0 for all Poly Haven assets, https://polyhaven.com/license (no attribution required; credited anyway).

| Asset | Type | Source page | Used in |
|---|---|---|---|
| metal_office_desk | model | https://polyhaven.com/a/metal_office_desk | Room 9C |
| modern_arm_chair_01 | model | https://polyhaven.com/a/modern_arm_chair_01 | Room 9C (Assessor) |
| SchoolChair_01 | model | https://polyhaven.com/a/SchoolChair_01 | Room 9C (Marcus) |
| mounted_fluorescent_lights | model | https://polyhaven.com/a/mounted_fluorescent_lights | Room 9C |
| binder_notebook | model | https://polyhaven.com/a/binder_notebook | Room 9C |
| round_wooden_table_01 | model | https://polyhaven.com/a/round_wooden_table_01 | Cafe |
| dining_chair_02 | model | https://polyhaven.com/a/dining_chair_02 | Cafe |
| hanging_industrial_lamp | model | https://polyhaven.com/a/hanging_industrial_lamp | Cafe |
| industrial_wall_lamp | model | https://polyhaven.com/a/industrial_wall_lamp | Cafe |
| potted_plant_02 | model | https://polyhaven.com/a/potted_plant_02 | Cafe |
| Sofa_01 | model | https://polyhaven.com/a/Sofa_01 | Apartment |
| desk_lamp_arm_01 | model | https://polyhaven.com/a/desk_lamp_arm_01 | Apartment |
| modular_industrial_pipes_01 | model | https://polyhaven.com/a/modular_industrial_pipes_01 | Tunnels |
| worn_metal_rack | model | https://polyhaven.com/a/worn_metal_rack | Lab / tunnels |
| medical_box | model | https://polyhaven.com/a/medical_box | Lab |
| utility_box_01 | model | https://polyhaven.com/a/utility_box_01 | Tunnels |
| power_box_01 | model | https://polyhaven.com/a/power_box_01 | Lab / tunnels |
| security_camera_01 | model | https://polyhaven.com/a/security_camera_01 | Lab |
| SchoolDesk_01 | model | https://polyhaven.com/a/SchoolDesk_01 | Lab |
| metal_tool_chest | model | https://polyhaven.com/a/metal_tool_chest | Lab |
| ladder_sectioned_01 | model | https://polyhaven.com/a/ladder_sectioned_01 | Tunnels |
| wall_clock | model | https://polyhaven.com/a/wall_clock | Lab |
| concrete_floor_worn_001 | texture | https://polyhaven.com/a/concrete_floor_worn_001 | Room 9C floor |
| concrete_wall_006 | texture | https://polyhaven.com/a/concrete_wall_006 | Room 9C wall |
| grey_plaster_02 | texture | https://polyhaven.com/a/grey_plaster_02 | ceilings, cafe walls |
| brushed_concrete | texture | https://polyhaven.com/a/brushed_concrete | corridor floor |
| dark_wooden_planks | texture | https://polyhaven.com/a/dark_wooden_planks | cafe floor |
| dark_wood | texture | https://polyhaven.com/a/dark_wood | cafe wainscot |
| unfinished_office_night | HDRI | https://polyhaven.com/a/unfinished_office_night | Room 9C reflections, cast lineup |
| warm_restaurant_night | HDRI | https://polyhaven.com/a/warm_restaurant_night | Cafe reflections |

Props were packed to GLB, textures converted to WebP, geometry meshopt-compressed (gltf-transform optimize with --flatten false --join false).

## Made for this project (no third-party license)
Tablet photograph, propaganda poster, window rain texture, cups and saucers (procedural), all set layouts and lighting.

## Fonts
Inter and Cormorant Garamond via Google Fonts (SIL Open Font License 1.1).

## Considered and not used
- Ready Player Me: service shut down January 31, 2026.
- Mixamo: raw character/animation files are not redistributable.
- three.js example characters (Michelle, Soldier, Xbot): Mixamo-derived, same redistribution concern.
- Quaternius / Kenney (CC0): clean but stylized low-poly, the toy-like look this rebuild is moving away from.

## Audio (original, CC0)
UI ticks and ambient beds in `public/assets/audio/` were synthesized for this project with ffmpeg
(sine tones and filtered noise; no third-party samples). Dedicated to the public domain (CC0).
Mapped per set: apartment, street, office/conf, cafe, stairwell, tunnels, dream, lab, void.
