---
title: Vowels
layout: default
nav_order: "3"
---
# Vowels

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>
___
# List of Vowels
- Although the consonants in the literature are the same as the recorded speaker, the vowels recorded by the `SwaTao` speaker differs from the expected vowels in the `Teochew Proper` literature

## Expected Vowels
- According to the `Teochew Proper` transcriptions, the below table maps the `Peng'im` Orthography to IPA

| Vowel IPA | Vowel Peng’im | IPA Transcription | Peng’im Transcription | SwaTao Gloss | Chinese Gloss | English Gloss |
| --------- | ------------- | ----------------- | --------------------- | ------------ | ------------- | ------------- |
| /i/       | i             | /mi/              | mi7                   | 面            | 面             | Noodle        |
| /e/       | ê             | /me/ /si/         | mê5 si7               | 暝时           | 夜晚            | Night         |
| /a/       | a             | /ma/              | ma5                   | 妈            | 妈             | Mom           |
| /o/       | o             | /mo/              | mo2                   | 毛            | 毛             | Fur           |
| /u/       | u             | /gu/              | ghu1                  | 牛            | 牛             | Cow           |
| /ɯ/       | e             | /kʰɯ/             | ke3                   | 去            | 去             | Go            |

| Expected Vowel Chart                        |
| ------------------------------------------- |
| ![](assets/vowels/Expected_Vowel_Chart.jpg) |

## Recorded Vowels
Before going into the details on the vowel identification, below details the process to obtain the Vowel Charts:
#### Vowel Calculation Method
1. Since the vowel was produced in a `/CV/` context, select only the portion where the consonant formant modulation is not present (vowel formants become stable)
2. Get `Formant`>`Formant Listing` from Praat
3. Take the median of the entire time series for `F2-F1` and `F1` values and plot them

### Recorded Vowel Chart with Original Vowels
- Based on the positions of `/ɯ/` and `/a/`, the there seems to be a slight lowering of `F2` in the vowel supposed to be `/ɯ/` and an extreme lowering of `F2` in the vowel supposed to be `/a/`

| Recorded Vowel Chart                                            |
| --------------------------------------------------------------- |
| ![Original Vowel Chart](assets/vowels/Original_Vowel_Chart.png) |

### Vowel Shift in `SwaTao`
- When listening to the recording combined with the new data, `SwaTao` seems to have these `/ɤ/` and `/ɑ/` rather than `/ɯ/` and `/a/`

| Peng'im | Expected Vowel | Recorded Vowel |
| ------- | -------------- | -------------- |
| a       | /a/            | /ɑ/            |
| e       | /ɯ/            | /ɤ/            

| Vowel IPA | Vowel Peng’im | IPA Transcription | Peng’im Transcription | SwaTao Gloss | Chinese Gloss | English Gloss |
| --------- | ------------- | ----------------- | --------------------- | ------------ | ------------- | ------------- |
| /a/       | /ɑ/           | /mɑ/              | ma5                   | 妈            | 妈             | Mom           |
| /ɯ/       | /ɤ/           | /kʰɤ/             | ke3                   | 去            | 去             | Go            |

| Description                                                 | Vowel Chart                                                             |
| ----------------------------------------------------------- | ----------------------------------------------------------------------- |
| Hypothesized Shifted Vowel Chart                            | ![Annotated Vowel Chart Image](assets/vowels/Annotated_Vowel_Chart.png) |
| Potential "Backing" shift from `Teochew Proper` to `SwaTao` | ![potential_vowel_shift image](assets/vowels/Potential_Vowel_Shift.png) |

### Possible Reasons For Vowel Shifting
- However, it is unclear whether this shift is due to:(1) variety, (2) speaker, or (3) speaking conditions of the normal speaker.

| Possible Reason For Shifting | Description of Reason                                                                                 | Finding                                                                                                                                                                                                                     |
| ---------------------------- | ----------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Variety                      | The `/ɯ/` and `/a/` vowel shift to `/ɤ/` and `/ɑ/` for all `SwaTao` speakers                          | (1) There is a `Backing` of the `/ɯ/` and `/a/` vowels from `Teochew Proper` to `SwaTao` under all conditions<br><br>(2) `SwaTao` speaker's phonological unit[^1] for those 2 vowels differs from `Teochew Proper`'s        |
| Speaking Conditions          | The `Backing` only occurs in limited conditions                                                       | (1) There is a `Backing` from `Teochew Proper` to `SwaTao` under certain conditions<br><br>(2) The phonological unit for the 2 vowels are the same in `SwaTao` and `Teochew Proper` but experience allophonic variation[^2] |
| Speaker Specific             | The vowel shift is only present in the native speaker recorded and not for other speakers of `SwaTao` | (1) There is no difference in vowels between both varieties<br><br>(2) The phonological units for both varieties are the same                                                                                               |
See Section (// TODO) for future investigation of vowel shifting.
___
# Vowel Spectrograms

____
[^1]: Phonological Unit refers to an abstract mental unit representing the information a speaker needs to decode (understand from a speech signal) or encode (produce) a given sound. More specifically, the Phonological Unit is likely a set of `Dynamical Systems` governing the movement of `Vocal Tract Constrictors` where the target `Constriction Location` (traditionally `Place of Articulation`) and `Constriction Degree` (traditionally `Manner of Articulation`) are the `goals` of each `Dynamical System` 
[^2]: Due to the `synergy` and `interaction` of the `Dynamical Systems` controlling each `Constrictor`--in this case, `Tongue Body`--`/ɯ/` and `/a/` have greater `Pharyngeal Constriction` 


