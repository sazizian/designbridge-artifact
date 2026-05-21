# designbridge-artifact
ICSE 2027

# DesignBridge Anonymous Replication Package

This repository contains the anonymous replication package for the submitted paper
"DesignBridge: Artifact-Aware AI-Assisted Constructive Reasoning for Multi-Objective Software Design Discussions."

The package includes:
1. prompts for all baselines and DesignBridge variants,
2. retrieval and model configuration files,
3. anonymized metadata for retained GitHub design discussions,
4. annotation and evaluation rubrics,
5. generated outputs and reasoning-state snapshots,
6. scripts for reproducing the reported tables.

The package is anonymized for double-anonymous review. Author-identifying metadata has been removed.

To reproduce the main tables:
1. create a Python environment,
2. install dependencies from requirements.txt,
3. run `bash analysis/run_all.sh`,
4. compare the generated CSV files in `results/` with the tables in the paper.

Some external LLM-generated outputs are provided as frozen outputs because API models may change over time. Scripts are provided to recompute aggregate metrics from the frozen outputs.
