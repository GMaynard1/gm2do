name: Vessel Issue
description: Describe an issue taking place on board a vessel
title: "[VESSEL ISSUE] <title>"
labels: ["task"]
assignees:
body:
- type: dropdown
  id: VesselName
  attributes:
    label: Vessel Name
    options:
    - Adie_Alden
    - Adventure
    - Alicia_Ann
    - BantryBay
    - Beast_of_Burden
    - Brooke_C
    - Charger
    - Christi_Caroline
    - Christy
    - Dawn_T
    - Debbie_Sue
    - Devocean
    - Donna_Marie
    - Dorcas_Anne
    - Dyrsten
    - Elizabeth_Katherine
    - Ellen_Diane
    - Excalibur
    - Finlander_I
    - Finlander_II
    - Flicka
    - Fremantle_Doctor
    - Happy_Trails
    - Hound_Dog
    - Illusion
    - Lady_Claire
    - Lady_Jane
    - Lady_Rebecca
    - Lery_Charles
    - Lina_Rose
    - Linda_Marie
    - Lisa_Ann_III
    - Mary_Elizabeth
    - Mary_K
    - Michelle_Jean_II
    - Miss Julie
    - Miss_Lilly
    - Mister_G
    - Moragh_K
    - Mussel_Point
    - Mystic
    - Nathaniel_Lee
    - Nicole_Leigh
    - Proud_Mary
    - Rachel Leah
    - Resolve
    - Rolex
    - Rueby
    - Sao_Paulo
    - Tenacious_II
    - Terri_Ann
    - Tina_Marie
    - Tom_Slaughter
    - Tribiah_Lee
    - Virginia_Marie
    - Virginia_Marise
    - Wendy_Lee
  validations:
    required: true
- type: input
  id: DateObserved
  attributes:
    label: Date Observed
    placeholder: YYYY-MM-DD
  validations:
    required: true
- type: textarea
  id: symptom
  attributes:
    label: Symptom
    placeholder: Please describe the symptom here
  validations:
    required: true
- type: textarea
  id: potentialFix
  attributes:
    label: Potential Fix
    placeholder: If you or the captain had an idea to fix the problem, please include it here
