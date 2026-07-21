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

- BPIC2012
- BPIC2013
- BPIC2014
- BPIC2015-1
- BPIC2015-2
- BPIC2015-3
- BPIC2015-4
- BPIC2015-5
