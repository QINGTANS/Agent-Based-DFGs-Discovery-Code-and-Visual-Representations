# Agent-Based DFG Discovery Code

This repository contains the code for discovering Agent-Based Directly-Follows Graphs (DFG) and generating their visual representations.

## Configuration

Before running the Jupyter Notebook, configure the following thresholds in the **first cell**:

- **`input_data_path`:** Path to the input event log.
- **`output_visualization_figure_folder_path`:** Folder where the generated figures will be saved.
- **`agent_type_behavior_filter_t1`:** A value between 0 and 1 that filters activity nodes in intra-agent-type behavioral models. A higher value retains fewer nodes.
- **`agent_type_interaction_filter_t2`:** A value between 0 and 1 that filters inter-agent-type interactions. A higher value retains fewer interactions.

After setting these thresholds, click **Run All** to execute the Jupyter Notebook and generate the Agent-Based DFG visualizations.

# Agent-Based DFG Visual Representations

This repository contains the visual representations of Agent-Based Directly-Follows Graphs (ADDs) generated from eight real-world BPIC event logs. For each event log, two folders are provided. Each folder contains multiple types of ADD visualizations generated using a different pair of threshold values.

### Threshold Settings

- **`t1_05_t2_01`**
  - Thresholds: `t1 = 0.5`, `t2 = 0.1`

- **`t1_09_t2_00`**
  - Thresholds: `t1 = 0.9`, `t2 = 0.0`

All visualizations within a folder are generated using the corresponding threshold configuration. The different threshold settings allow users to compare the effects of filtering on the generated Agent-Based DFG visualizations.

### Datasets

The repository includes visualizations generated from the following eight BPIC event logs:

- BPIC2012: https://doi.org/10.4121/uuid:3926db30-f712-4394-aebc-75976070e91f
- BPIC2013: https://doi.org/10.4121/uuid:a7ce5c55-03a7-4583-b855-98b86e1a2b07
- BPIC2014: https://doi.org/10.4121/uuid:3cfa2260-f5c5-44be-afe1-b70d35288d6d
- BPIC2015-1: https://doi.org/10.4121/uuid:a0addfda-2044-4541-a450-fdcc9fe16d17
- BPIC2015-2: https://doi.org/10.4121/uuid:63a8435a-077d-4ece-97cd-2c76d394d99c
- BPIC2015-3: https://doi.org/10.4121/uuid:ed445cdd-27d5-4d77-a1f7-59fe7360cfbe
- BPIC2015-4: https://doi.org/10.4121/uuid:679b11cf-47cd-459e-a6de-9ca614e25985
- BPIC2015-5: https://doi.org/10.4121/uuid:b32c6fe5-f212-4286-9774-58dd53511cf8
