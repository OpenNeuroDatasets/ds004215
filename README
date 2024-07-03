# The National Institute of Mental Health (NIMH) Research Volunteer (RV) Data Set

A comprehensive dataset characterizing healthy research volunteers in terms of clinical assessments, mood-related psychometrics, cognitive function neuropsychological tests, structural and functional magnetic resonance imaging (MRI), along with diffusion tensor imaging (DTI), and a comprehensive magnetoencephalography battery (MEG).

In addition, blood samples are currently banked for future genetic analysis.  All data collected in this protocol are broadly shared in the OpenNeuro repository, in the Brain Imaging Data Structure (BIDS) format.  In addition, task paradigms and basic pre-processing scripts are shared on GitHub.  This dataset is unprecedented in its depth of characterization of a healthy population and will allow a wide array of investigations into normal cognition and mood regulation.

This dataset is licensed under the [Creative Commons Zero (CC0) v1.0 License](https://creativecommons.org/publicdomain/zero/1.0/).

## Release Notes

### Release v2.0.0

The v2.0.0 dataset release includes data collected since 2020-06-03 (cut-off date for v1.0.0). Notable changes in this release:

1. Phenotype files now have two new columns `visit` and `age_at_visit` to distinguish between various visits, and intervals between visits. 
2. Follow-up online survey data included.
3. Replaced Beck Anxiety Inventory (BAI) and Beck Depression Inventory-II (BDI-II) with General Anxiety Disorder-7 (GAD7) and Patient Health Questionnaire 9 (PHQ9) surveys, respectively.
4. Discontinued the Perceived Health rating survey.
5. Added Brief Trauma Questionnaire (BTQ) and Big Five personality survey to online screening questionnaires.
6. MRI:
   - Replaced ADNI-3 resting state sequence with a multi-echo sequence with higher spatial resolution.
   - Replaced field map scans with a shorter reversed-blipped EPI scan.
7. MEG:
   - Some participants have 6-minute empty room data instead of the shorter duration empty room acquisition.

See the [CHANGES](./CHANGES.txt) file for complete version-wise changelog.


## Participant Eligibility

To be eligible for the study, participants need to be medically healthy adults over 18 years of age with the ability to read, speak and understand English.  All participants provided electronic informed consent for online pre-screening, and written informed consent for all other procedures.  Participants with a history of mental illness or suicidal or self-injury thoughts or behavior are excluded.  Additional exclusion criteria include current illicit drug use, abnormal medical exam, and less than an 8th grade education or IQ below 70.  Current NIMH employees, or first degree relatives of NIMH employees are prohibited from participating.  Study participants are recruited through direct mailings, bulletin boards and listservs, outreach exhibits, print advertisements, and electronic media.

## Clinical Measures

All potential volunteers visit [the study website](https://nimhresearchvolunteer.ctss.nih.gov), check a box indicating consent, and fill out preliminary screening questionnaires.  The questionnaires include basic demographics, the World Health Organization Disability Assessment Schedule 2.0 (WHODAS 2.0), the DSM-5 Self-Rated Level 1 Cross-Cutting Symptom Measure, the DSM-5 Level 2 Cross-Cutting Symptom Measure - Substance Use, the Alcohol Use Disorders Identification Test (AUDIT), the Edinburgh Handedness Inventory, and a brief clinical history checklist.  The WHODAS 2.0 is a 15 item questionnaire that assesses overall general health and disability, with 14 items distributed over 6 domains: cognition, mobility, self-care, “getting along”, life activities, and participation.  The DSM-5 Level 1 cross-cutting measure uses 23 items to assess symptoms across diagnoses, although an item regarding self-injurious behavior was removed from the online self-report version.  The DSM-5 Level 2 cross-cutting measure is adapted from the NIDA ASSIST measure, and contains 15 items to assess use of both illicit drugs and prescription drugs without a doctor’s prescription.  The AUDIT is a 10 item screening assessment used to detect harmful levels of alcohol consumption, and the Edinburgh Handedness Inventory is a systematic assessment of handedness.  These online results do not contain any personally identifiable information (PII).  At the conclusion of the questionnaires, participants are prompted to send an email to the study team. These results are reviewed by the study team, who determines if the participant is appropriate for an in-person interview.

Participants who meet all inclusion/exclusion criteria are scheduled for an in-person screening visit.  At this visit, participants receive a Structured Clinical Interview for DSM-5 Disorders (SCID-5), the Beck Depression Inventory-II (BDI-II), Beck Anxiety Inventory (BAI), the Kaufman Brief Intelligence Test, Second Edition (KBIT-2), and the NIH Toolbox Cognition Battery.  The purpose of these cognitive and psychometric tests is two-fold.  First, these measures are designed to provide a sensitive test of psychopathology.  Second, they provide a comprehensive picture of cognitive functioning, including mood regulation.  The SCID-5 is a structured interview, administered by a clinician, that establishes the absence of any DSM-5 axis I disorder.  The BDI-II is a 21 item self-report measure that assesses the presence and severity of depressive symptoms, while the BAI is a 21 item self-report measure assessing the presence and severity of anxiety symptoms.  The KBIT-2 is a brief (20 minute) assessment of intellectual functioning administered by a trained examiner.  There are three subtests, including verbal knowledge, riddles, and matrices.  The NIH Toolbox Cognition Battery consists of a series of seven tests.  A flanker inhibitory control and attention task assesses the constructs of attention and executive functioning.  Executive functioning is also assessed in the battery using a dimensional change card sort test.  Episodic memory is evaluated using a picture sequence memory test, while working memory is evaluated using a list sorting test.  The battery includes two language tests, a picture vocabulary test and an oral reading recognition test.  Finally, processing speed is assessed using a pattern comparison processing speed test.

## Biological and physiological measures

Biological and physiological measures are acquired, including blood pressure, pulse, weight, height, and BMI.  Blood and urine samples are taken and a complete blood count, acute care panel, hepatic panel, thyroid stimulating hormone, viral markers (HCV, HBV, HIV), c-reactive protein, creatine kinase, urine drug screen and urine pregnancy tests are performed.  In addition, blood samples for genetic testing are collected and banked, and genetic information will be shared once it is available.

## Imaging Studies

Participants were given the option to enroll in optional magnetic resonance imaging (MRI) and magnetoencephalography (MEG) studies.

### MRI

The MRI protocol used was initially based on the ADNI-3 basic protocol, but was later modified to include portions of the ABCD protocol in the following manner:

1. The T1 scan from ADNI3 was replaced by the T1 scan from the ABCD protocol.
2. The Axial T2 2D FLAIR acquisition from ADNI2 was added, and fat saturation turned on.
3. Fat saturation was turned on for the pCASL acquisition.
4. The high-resolution in-plane hippocampal 2D T2 scan was removed, and replaced with the whole brain 3D T2 scan from the ABCD protocol (which is resolution and bandwidth matched to the T1 scan).
5. The slice-select gradient reversal method was turned on for DTI acquisition, and reconstruction interpolation turned off.
6. Scans for distortion correction were added (reversed-blip scans for DTI and resting state scans).
7. The 3D FLAIR sequence was made optional, and replaced by one where the prescription and other acquisition parameters provide resolution and geometric correspondence between the T1 and T2 scans.

### MEG

The optional MEG studies were added to the protocol approximately one year after the study was initiated, thus there are relatively fewer MEG recordings in comparison to the MRI dataset.  MEG studies are performed on a 275 channel CTF MEG system.  The position of the head was localized at the beginning and end of the recording using three fiducial coils.  These coils were placed 1.5 cm above the nasion, and at each ear, 1.5 cm from the tragus on a line between the tragus and the outer canthus of the eye.  For some participants, photographs were taken of the three coils and used to mark the points on the T1 weighted structural MRI scan for co-registration.  For the remainder of the participants, a BrainSight neuro-navigation unit was used to coregister the MRI, anatomical fiducials, and localizer coils directly prior to MEG data acquisition.


## Specific Survey and Test Data within Data Set

### 1. Preliminary Online Screening Questionnaires

|  Survey or Test                                                             |  BIDS TSV Name                 |
| --------------------------------------------------------------------------- | ------------------------------ |
|  Alcohol Use Disorders Identification Test (AUDIT)                          |  audit.tsv                     |
|  Brief Trauma Questionnaire (BTQ)                                           |  btq.tsv                       |
|  Big-Five Personality                                                       |  big_five_personality.tsv      |
|  Demographics                                                               |  demographics.tsv              |
|  Drug Use Questionnaire                                                     |  drug_use.tsv                  |
|  Edinburgh Handedness Inventory (EHI)                                       |  ehi.tsv                       |
|  Health History Questions                                                   |  health_history_questions.tsv  |
|  Health Rating                                                              |  health_rating.tsv             |
|  Mental Health Questions                                                    |  mental_health_questions.tsv   |
|  World Health Organization Disability Assessment Schedule 2.0 (WHODAS 2.0)  |  whodas.tsv                    |

### 2. On-Campus In-Person Screening Visit

|  Survey                                                                                      |  BIDS TSV Name                |
| -------------------------------------------------------------------------------------------- | ----------------------------- |
|  Adverse Childhood Experiences (ACEs)                                                        |  ace.tsv                      |
|  Beck Anxiety Inventory (BAI)                                                                |  bai.tsv                      |
|  Beck Depression Inventory-II (BDI-II)                                                       |  bdi.tsv                      |
|  Clinical Variable Form                                                                      |  clinical_variable_form.tsv   |
|  Family Interview for Genetic Studies (FIGS)                                                 |  figs.tsv                     |
|  General Anxiety Disorder-7 (GAD7)                                                           |  gad7.tsv                     |
|  Kaufman Brief Intelligence Test 2nd Edition (KBIT-2) and Vocabulary Assessment Scale (VAS)  |  kbit2_vas.tsv                |
|  NIH Toolbox Cognition Battery                                                               |  nih_toolbox.tsv              |
|  Patient Health Questionnaire 9                                                              |  phq9.tsv                     |
|  Perceived Health Rating                                                                     |  perceived_health_rating.tsv  |
|  Satisfaction Survey                                                                         |  satisfaction.tsv             |
|  Structured Clinical Interview for DSM-5 Disorders (SCID-5)                                  |  scid5.tsv                    |

|  Test                                    |  BIDS TSV Name              |
| ---------------------------------------- | --------------------------- |
|  Acute Care Panel                        |  acute_care.tsv             |
|  Blood Chemistry                         |  blood_chemistry.tsv        |
|  Complete Blood Count with Differential  |  cbc_with_differential.tsv  |
|  Hematology Panel                        |  hematology.tsv             |
|  Hepatic Function Panel                  |  hepatic.tsv                |
|  Infectious Disease Panel                |  infectious_disease.tsv     |
|  Lipid Panel                             |  lipid.tsv                  |
|  Other Panel                             |  other.tsv                  |
|  Urinalysis                              |  urinalysis.tsv             |
|  Urine Chemistry                         |  urine_chemistry.tsv        |
|  Vitamin Levels                          |  vitamin_levels.tsv         |

### 3. Optional On-Campus In-Person MRI Visit

|  Survey         |  BIDS TSV Name      |
| --------------- | ------------------- |
|  MRI Variables  |  mri_variables.tsv  |


## Preparation Notes

In many of the Clinical Measures data files, there exist `-999` values.  `-999` means there was no response though a response was possible.  The question may have been skipped over by the participant or the question flow.  `-777` appears in the Edinburgh Handedness Inventory (EHI) as well.  `-777` means there is no data available for a response.  The question was not presented or asked to the participant.

The data were prepared using the following tools and filename mappings.

### Clinical Measures Data

The `ctdb_clean_up.ipynb` Jupyter Notebook contains the python functions used to clean and convert the spreadsheet downloaded from CTDB to BIDS-standard TSV files as well as their respective data dictionaries converted to BIDS-standard JSON files.

### Biological and Physiological Measures Data

The `cris_clean_up.ipynb` Jupyter Notebook contains the Python functions used to clean and convert the spreadsheet with clinical measures to BIDS-standard TSV files and their data dictionaries to BIDS-standard JSON files.

### BIDS-standard MEG Files

Data collected by the NIMH MEG Core was converted to BIDS-standard files using the MNE BIDS package.  Associated notebooks: `1_mne_bids_extractor.ipynb` & `2_bids_editor.ipynb`.

### BIDS-standard MRI

We used the `heudiconv` tool to convert MRI DICOM files to BIDS-standard files with the associated script: `heuristic_rvol.py`.  A modified workflow of `pydeface` was used to deface structural scans with the associated notebook: `modified-workflow-pydeface.ipynb`

Each participant received either the ADNI3 or the ABCD protocol, not both, during their MRI/MEG visit.  T1w scans with acquisition label `fspgr` are ADNI3 protocol sequence and scans with `mprage` acquisition labels are ABCD protocol sequence.

### OpenNeuro BIDS File/Folder Tree

Below is a BIDS-compliant file/folder tree as it appears for subjects on OpenNeuro.

```shell
sub-ON<subject>
    └── ses-01
        ├── anat
        │   └── sub-ON<subject>_ses-01_acq-<desc>_run-<index>_<suffix>.<json|nii.gz>
        ├── asl
        │   └── sub-ON<subject>_ses-01_run-<index>_asl.<json|nii.gz>
        ├── dwi
        │   └── sub-ON<subject>_ses-01_run-<index>_dwi.<bvec|bval|json|nii.gz>
        ├── fmap
        │   └── sub-ON<subject>_ses-01_acq-<desc>_dir-<direction>_run-<index>_epi.<bvec|bval|json|nii.gz>
        ├── func
        │   └── sub-ON<subject>_ses-01_task-<taskname>_run-<index>_<suffix>.<json|nii.gz>
        ├── meg
        │   ├── sub-ON<subject>_ses-01_task-<taskname>_run-01_<meg|coordsystem>.json
        │   ├── sub-ON<subject>_ses-01_task-<taskname>_run-01_<channels|events>.tsv
        │   └── sub-ON<subject>_ses-01_task-<taskname>_run-01_meg.ds
        │       ├── BadChannels
        │       ├── bad.segments
        │       ├── ClassFile.cls
        │       ├── MarkerFile.mrk
        │       ├── params.dsc
        │       ├── processing.cfg
        │       ├── sub-ON<subject>_ses-01_task-<taskname>_run-01_meg.<extension>
        │       └── sub-ON<subject>_ses-01_task-<taskname>_run-01.xml
        └── sub-ON<subject>_ses-01_scans.<json|tsv>
```

Definitions:

- `<subject>` = subject number
- `<taskname>` = task name: `airpuff`, `artifact`, `gonogo`, `haririhammer`, `movie`, `oddball`, `sternberg`
- `<desc>` = placeholder for acquisition label for a given suffix
- `<direction>` = flipped, unflipped
- `<index>` = run number/index
- `<suffix>` = placeholder to indicate the scan type
    - `T1w`: `<desc>` = `fspgr`, `mprage`, `fse`, `highreshippo`
    - `T2w`: `<desc>` = `abcdcube`, `cube`, `frfse`
    - `FLAIR`: `<desc>` = `adni2d`, `2d`, `3d`, `t2`
    - `epi`: `<desc>` = `dwib1000`, `dwi`, `resting`
    - `T2star`
    - `bold`
    - `meg`
    - `asl`
- `<extension>`: indicates meg data files' type = `acq`, `bak`, `hc`, `hist`, `infods`, `meg4`, `newds`, `res4`, `xml`
