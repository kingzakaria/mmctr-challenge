# WWW 2025 MM-CTR Challenge: Multimodal CTR Prediction

University project based on the EReL@MIR Multimodal CTR Prediction Challenge (WWW 2025).

## Links
- Challenge page: https://erel-mir.github.io/challenge/mmctr-track2/
- Codabench portal: https://www.codabench.org/competitions/5372/
- Dataset (MicroLens-1M): https://recsys.westlake.edu.cn/MicroLens_1M_MMCTR/
- Official baseline: https://github.com/reczoo/WWW2025_MMCTR_Challenge

## Goal
Predict the probability that a user clicks on an item (pCTR), using click
history and multimodal item embeddings. Metric: AUC.

## Chosen task
Task 2 only (improve the CTR model on the provided embeddings).

## Constraints
- No data outside the provided dataset
- One neural network only (no ensembles, no tree models)
- Trained end-to-end on the given features and split

## Repo structure
- `configs/`: experiment configuration files
- `data/`: dataset (not committed)
- `docs/`: notes and experiment log
- `notebooks/`: data exploration
- `src/`: our code
- `submissions/`: generated submission files (not committed)

## Roadmap
- [x] Step 1: create the repo
- [x] Step 2: folder structure and .gitignore
- [ ] Step 3: environment and data download
- [ ] Step 4: run the official baseline
- [ ] Step 5: data exploration
- [ ] Step 6: build and improve our model
- [ ] Step 7: generate the submission

## License
MIT