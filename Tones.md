---
title: Tones
layout: default
nav_order: "4"
---
# Tones

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>
___
# Tones Introduction
- Commonly referred to as `tones`, tones are `Fundamental Frequency` or `F0` or `pitch` modulations (changes) throughout an utterance
	- The modulation of `F0` throughout an utterance is known as a `Pitch Contour` which can be plotted as `F0 vs. Time`
- From a `Gestural Framework`, the `goal` of `High Tone` or `Low Tone` are achieved by constrictions of the `articulators` or muscles in the lower portion of the `Vocal Tract`

|                  | High Tone                                             | Low Tone                                |
| ---------------- | ----------------------------------------------------- | --------------------------------------- |
| Tension Goal     | Increase Longitudinal Tension                         | Decrease Vertical Tension               |
| Articulator Goal | Increase Angle between Cricoid and Thyroid Cartilages | Lower Larynx                            |
| Muscle Involved  | Crico-thyroid muscle                                  | Strap muscle (sterno-hyoid/thyrohiyoid) |

# List of Tones
#### Tone Class
- In `Teochew` there are 2 `Tone Classes`: either `low`[^1] or `high`[^2] `F0`
	- `low` means that the F0 begins low
	- `high` means that the F0 beings low
	- Note: after the initial onset pitch, the utterance may be modulated (either go higher or lower depending on the `Tone Category`)

| Tone Class | Starting F0 | Teochew Transcription | Corresponding Peng'im Tones |
| ---------- | ----------- | --------------------- | --------------------------- |
| high       | high        | 阴                     | `1` `2` `3` `4`             |
| low        | low         | 阳                     | `5` `6` `7` `8`             |
#### Tone Category
- In addition to `Tone Class`, each Tone can be modulated with a `Tone Category` (either increase or decrease `F0` depending on the onset `F0` or `Tone Class`)

| IPA Tone Example          | Corresponding Peng'im Tones | F0 Modulation                                                                                                       | English Transcription | Teochew Transcription |
| ------------------------- | --------------------------- | ------------------------------------------------------------------------------------------------------------------- | --------------------- | --------------------- |
| `33`<br>`55`              | `1`<br>`5`                  | Constant                                                                                                            | Level                 | 平                     |
| `53`<br><br><br>`35`      | `2`<br><br><br>`6`          | Decrease F0 if `Tone Class` is High<br><br>Increase F0 if `Tone Class` (starting F0) is Low                         | Rising                | 上                     |
| `213`<br><br><br><br>`11` | `3`<br><br><br><br>`7`      | Decrease and then Increase if `Tone Class` is High[^4]                      <br>Constant if `Tone Class` is Low[^5] | Departing             | 去                     |
| `2`<br>`5`                | `4`<br>`8`                  | Constant (Glottal Stop final)                                                                                       | Enetering             | 入                     |

- Each of the categories and tones combine combinatorially to yield the tone table below

```
Total_Tones = Number_Tone_Classes * Number_Tone_Types

Total_Tones_in_SwaTao = 2 Tone Classes * 4 Tone Types
Total_Tones_in_SwaTao = 8
```

## Tone Classification
- The table below reiterates the information above and maps the relationship between **Tone Class and Tone Category** with **IPA `pitch contour`**, **`Peng'im` tone number**, and written **Chinese tone orthography**

| IPA Number[^3] | Peng’im Tone # | Tone Type (English) | Tone Class (English) | Tone Type (Teochew) | Tone Class<br>(Teochew) |
| -------------- | -------------- | ------------------- | -------------------- | ------------------- | ----------------------- |
| 33             | 1              | High                | Level                | 阴                   | 平                       |
| 53             | 2              | High                | Rising               | 阴                   | 上                       |
| 213            | 3              | High                | Departing            | 阴                   | 去                       |
| 2              | 4              | High                | Entering             | 阴                   | 入                       |
| 55             | 5              | Low                 | Level                | 阳                   | 平                       |
| 35             | 6              | Low                 | Rising               | 阳                   | 上                       |
| 11             | 7              | Low                 | Departing            | 阳                   | 去                       |
| 5              | 8              | Low                 | Entering             | 阳                   | 入                       |

___
# Pitch Contour

## Discrepancies
____
[^1]: Low is also called "Light" or `阳` in some literature
[^2]: High also called "Dark" or `阴` in some literature
[^3]: The IPA tone scale from `1`-`5` represents the range of `F0` values for a speaker where `1` is the highest `pitch`/`f0` and `5` is the lowest `pitch`/`F0
[^4]: Similar to Mandarin `third tone`. In addition, this is the only `Teochew` tone with more than one pitch gesture in the modulation
[^5]: See the [Pitch Contour](#Pitch-Contour) section for the discrepancy between the expected "constant" tone versus the recorded decrease in `F0`