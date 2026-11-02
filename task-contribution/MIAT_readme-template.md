> ## How to use this template — delete this box before publishing
>
> - This template is already formatted in Markdown. Download it (click on the 3 dots next to the search bar on the right; just above the file), complete it and save or rename the file as `README.md`; If you add it to your GitHub repository, it will then display the headings, tables, and lists in the intended format. See also example repository in case something is unclear (https://github.com/carlacz/MBRT/PsychoPy-local).
> - Text in [square brackets] should be **replaced** with information about the task.
> - Text beginning with [If applicable: ...] should be completed **when relevant** and otherwise deleted.
> - Guidance in highlighted block quotes ("Guidance — delete before publishing: ...") should be **deleted before** publishing.
> - Please keep the main sections in the specified order and follow the template content as far as possible so that repositories remain consistent.
> - Only one functional task implementation is required. The task does not need to be provided in different software packages or deployment modes. In case multiple implementations are provided, consider using a main README.md for general task information (see https://github.com/carlacz/MBRT) and links to implementation folders. Each folder can contain a separate README.md beginning with the "Repository information" section (see https://github.com/carlacz/MBRT/PsychoPy-local).
> - Language localization and adaptable experiment parameters are not required. 

# [Full task name] ([task abbreviation])

Available in **[language(s)]**.

The **[full task name] ([task abbreviation])** is a behavioural paradigm designed to assess [movement imagery ability or process]. [Briefly explain what participants do and which outcomes are measured.] If you are interested in assessing broader movement imagery ability, visit the **Movement Imagery Ability Task Platform** (https://movementimageryability.github.io/) for an overview of open-source behavioural tasks.

[Briefly describe the theoretical or empirical background of the task and cite the original, adapted, or validation studies.]

This repository contains the materials for an open-source implementation of the [task abbreviation] using **[software]** for **[local/online]** use. [State which published task version or study this implementation is based on.]

Subsequent updates to [software/backend] may require adjustments. As developers, we are not responsible for adapting the task to every software update or use case.

[If applicable: Add image or gif of the task to demonstrate it]

## Repository information

**Author(s):** [Name(s)] 
**Last updated:** [DD/MM/YYYY]  
**Software used:** [Software and version; add the backend or hosting service if applicable]  
**Experiment type:** [Local/online]  
**Language(s) available:** [Language(s); add ISO codes if they are used in the experiment]  

This experiment is built using [software and version] and is intended for **[local/online] execution**. [If applicable: It uses the [backend/export] and is hosted via [hosting service].] Please use the specified version and backend because other versions or backends may behave unexpectedly.

[If relevant: Briefly describe how the experiment is implemented and any important deployment-specific feature.]

If you are unfamiliar with [software/backend], please refer to the [official documentation](link). This README describes this specific **[task abbreviation] [software, local/online]** implementation rather than the general use of the software.

## Setup instructions

**Requirements:** [Software and version; add the required backend, packages, hosting account/server, or supported browsers if applicable].

[State which raw output files are created and whether a data-preparation script is provided.]

**Step-by-step instructions:**

1. Download and unzip the complete repository into a dedicated folder.
2. Open `[main_experiment_file]` in [software].
3. [If applicable: Adapt the experiment settings.]
4. [Test the task locally or in a browser.]
5. [For online tasks: Export or sync the experiment, activate it on the hosting service, and generate a participant link.]
6. [State where the raw data are saved or how they are downloaded.]
7. [If provided: Process the data using `[data_preparation_script]`.]

## Technical details

The unzipped repository contains:

- `[main_experiment_file]`: Main experiment file.
- `[messages_or_materials_file/folder]`: [Contents].
- `[stimuli_folder]`: [Contents].
- `[data_folder]`: Storage location for [local/downloaded] data.
- [If applicable: `[data_preparation_script]`: [Purpose and output].]
- [If applicable: `[language_localiser_file]`: Language names and ISO codes.]

[If applicable: Explain how the included language-localization system works and how users can add a translation. See the [MBRT repository](https://github.com/carlacz/MBRT/PsychoPy-local) for an example.]


## Experiment settings

> **Guidance — delete before publishing:** Adaptable experiment parameters are not required. If the task does not include them, delete the entire “Experiment settings” section. If they are included, document them as shown below. The [MBRT repository](https://github.com/carlacz/MBRT/tree/main/PsychoPy-local#experiment-settings-parameters-to-choose) can be used as an example.

[Explain where, when, and by whom the settings are selected.]

### Available parameters

| Variable | Options | Description |
| :--- | :--- | :--- |
| `[variable_name]` | [Options, **default**] | [What the parameter changes] |
| `[variable_name]` | [Options, **default**] | [What the parameter changes] |

### Changing the defaults

[Provide software-specific steps. Name the exact sequence, routine, component, item, or script to edit.]

[If applicable: Explain how to disable settings selection or let participants select particular settings.]

## Demographic questions

> **Guidance — delete before publishing:** Demographic questions are not required. Delete this section if none are included.

[If included: List the demographic questions, briefly state their purpose, and explain how to disable them.]

## Saving and exporting

1. Save the experiment.
2. [If applicable: For online tasks, export or sync it to the hosting service.]
3. Test the complete task and check the resulting data before data collection.

## Participant workflow

1. **[Stage]:** [Description].
2. **[Stage]:** [Description].
3. **Practice block:** [Number and type of trials; feedback].
4. **Test block(s):** [Number and organization of blocks/trials; breaks; conditions].
5. **Completion:** [Final screen or redirection].

### [Task abbreviation] trial procedure

The sequence of a single trial is as follows:

1. **[Event]:** [e.g., stimulus/instruction and duration].
2. **[Event]:** [e.g., response and termination rule].
3. **[Event]:** [e.g., feedback or inter-trial interval].

## Output

> **Guidance — delete before publishing:** State where raw data are stored or downloaded, the file type and naming convention, whether files contain one participant/run or grouped data, whether files may be renamed, and how the data preparation script is run and what it creates. See see [MBRT repository](https://github.com/carlacz/MBRT/tree/main/PsychoPy-local#output) as an example.

[Describe the raw output, filename pattern, unit, and storage or download location.]

[If applicable: State where files must be placed and whether they may be renamed.]

[Describe what happens in the data preparation script (this example may not fit all tasks, adapt accordingly): 
The provided `[data_preparation_script]` reads [input files], extracts [relevant observations], and saves `[processed_output_file]` in `[output_folder]`. To prepare the data, open the script and [source/run] it. The script creates:

- `[trial_level_dataset]`: [One row per trial/response/movement].
- `[participant_level_dataset]`: [One row per participant and included summary variables].

> **Note:** The script assumes the standard experiment and output structure. If the experiment is modified beyond the documented settings, the script may require adaptation. Raw data should be checked before analysis.

### Variable documentation

> **Guidance — delete before publishing:** Document the variables contained in the provided raw or processed output.

#### `[trial_level_dataset]`

| Variable name | Type | Description |
| :--- | :--- | :--- |
| `[variable_name]` | [Type] | [Meaning, unit, and coding] |
| `[variable_name]` | [Type] | [Meaning, unit, and coding] |

#### `[participant_level_dataset]`

| Variable name | Type | Description |
| :--- | :--- | :--- |
| `[variable_name]` | [Type] | [Meaning, unit, and coding] |
| `[variable_name]` | [Type] | [Meaning, unit, and coding] |

## Version history

| Date | Changes |
| :--- | :--- |
| [DD/MM/YYYY] | [Briefly describe the changes (not for formatting changes or correction of typos) made since the previous version] |
| [DD/MM/YYYY] | Initial release. |

## Reference

Please cite [full reference with DOI or stable URL] when using this resource.

Before collecting data, always test the experiment and check the data output. Contributions are welcome.
