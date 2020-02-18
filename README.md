# Awesome Temporal Action Localization


Papers



- [DBS](#1)	AAAI-2019	Video Imprint Segmentation for Temporal Action Detection in Untrimmed Videos	[code]
- GTAN	CVPR-2019	Gaussian Temporal Awareness Networks for Action Localization	[code]
- BMN	ICCV-2019	BMN: Boundary-Matching Network for Temporal Action Proposal Generation	[code]
- TAL-Net	CVPR-2018	Rethinking the Faster R-CNN Architecture for Temporal Action Localization	[code]
- RAM	TMM-2019	Graph Convolutional Networks for Temporal Action Localization	[code]
- PGCN	ICCV-2019	G-TAD: Sub-Graph Localization for Temporal Action Detection	[code]
- C-TCN	arXiv	Deep Concept-wise Temporal Convolutional Networks for Action Localization	[code]
- G-TAD	arXiv	G-TAD: Sub-Graph Localization for Temporal Action Detection	[code]
- CMCS	CVPR-2019	Completeness Modeling and Context Separation for Weakly Supervised Temporal Action Localization	[code]
- STAR	AAAI-2019	Segregated Temporal Assembly Recurrent Networks for Weakly Supervised Multiple
- Action Detection	[code]
- CleanNet	ICCV-2019	Weakly Supervised Temporal Action Localization through Contrast based Evaluation Networks	[code]
- TSM	ICCV-2019	Temporal Structure Mining for Weakly Supervised Action Detection	[code]
- IWO-Net	TIP-2019	Breaking Winner-Takes-All: Iterative-Winners-Out Networks for Weakly Supervised Temporal Action Localization	[code]
- BM	ICCV-2019	Weakly-supervised Action Localization with Background Modeling	[code]
- Action-Search	ECCV-2018	Action Search: Spotting Actions in Videos and Its Application to Temporal Action Localization	[code]
- BSN	ECCV-2018	BSN: Boundary Sensitive Network for Temporal Action Proposal Generation	[code]
- TPC	AAAI-2018	Exploring Temporal Preservation Networks for Precise Temporal Action Localization	[code]
- Self-Ad	AAAI-2018	A Self-Adaptive Proposal Model for Temporal Action Detection based on Reinforcement Learning	[code]
- One-Shot	CVPR-2018	One-Shot Action Localization by Learning Sequence Matching Network	[code]
- STPN	CVPR-2018	Weakly Supervised Action Localization by Sparse Temporal Pooling Network	[code]
- AutoLoc	ECCV-2018	Weakly-supervised Temporal Action Localization in Untrimmed Videos	[code]
- W-TALC	ECCV-2018	W-TALC: Weakly-supervised Temporal Activity Localization and Classification	[code]
- UNet	CVPR-2017	UntrimmedNets for Weakly Supervised Action Recognition and Detection	[code]
- H&S	ICCV-2017	Hide-and-Seek: Forcing a Network to be Meticulous for Weakly-supervised Object and Action Localization	[code]
- CDC	CVPR-2017	CDC: Convolutional-De-Convolutional Networks for Precise Temporal Action Localization in Untrimmed Videos	[code]
- SMS	CVPR-2017	Temporal Action Localization by Structured Maximal Sums	[code]
- SSN	ICCV-2017	Temporal Action Detection with Structured Segment Networks	[code]
- R-C3D	ICCV-2017	R-C3D: Region Convolutional 3D Network for Temporal Activity Detection	[code]
- TCN	ICCV-2017	Temporal Context Network for Activity Localization in Videos	[code]
- TURN	ICCV-2017	TURN TAP: Temporal Unit Regression Network for Temporal Action Proposals	[code]
- SST	ICCV-2017	SST: Single-Stream Temporal Action Proposals	[code]
- SCC	CVPR-2017	SCC: Semantic Context Cascade for Efficient Action Detection	[code]
- FG	CVPR-2016	End-to-end Learning of Action Detection from Frame Glimpses in Videos	[code]
- PSDF	CVPR-2016	Temporal Action Localization with Pyramid of Score Distribution Features	[code]
- SLM	CVPR-2016	Temporal Action Detection Using a Statistical Language Model	[code]
- S-CNN	CVPR-2016	Temporal Action Localization in Untrimmed Videos via Multi-stage CNNs	[code]
- DAPs	ECCV-2016	DAPs: Deep Action Proposals for Action Understanding	[code]



> | Method | C/J  | THUMOS14 |         |         |         |         |         |         | ActivityNet v1.3 |          |          |         | ActivityNet v1.2 |          |          |         |
> | :----- | :--: | -------- | ------- | ------- | ------- | ------- | ------- | ------- | :--------------: | :------: | :------: | ------- | ---------------- | -------- | -------- | ------- |
> |       		|      			| IoU@0.1  	| IoU@0.2 	| IoU@0.3 	| IoU@0.4 | IoU@0.5 	| IoU@0.6 	| IoU@0.7 	| 	    IoU@0.5      	| IoU@0.75 	| IoU@0.95 	| IoU@Avg 	| IoU@0.5          	| IoU@0.75 	| IoU@0.95 	| IoU@Avg 	|
> |	<span id = "1">[[DBS]](#1)</span>	|	`AAAI-2019`	|	56.7	|	54.7	|	50.6	|	43.1	|	34.3	|	24.4	|	14.7	|	43.2	|	25.8	|	6.1	|	26.1	|		|		|		|		|
> |	GTAN	|	CVPR-2019	|	69.1	|	63.7	|	57.8	|	47.2	|	38.8	|	-	|	-	|	52.61	|	34.14	|	8.91	|	34.31	|		|		|		|		|
> |	BMN	|	ICCV-2019	|	-	|	-	|	56	|	47.4	|	38.8	|	29.7	|	20.5	|	50.07	|	34.78	|	8.29	|	33.85	|		|		|		|		|
> |	TAL-Net	|	CVPR-2018	|	59.8	|	57.1	|	53.2	|	48.5	|	42.8	|	33.8	|	20.8	|	38.23	|	18.3	|	1.3	|	20.22	|		|		|		|		|
> |	RAM	|	TMM-2019	|	65.4	|	63.1	|	58.8	|	52.7	|	43.7	|	-	|	-	|	36.99	|	23.1	|	3.34	|	23.03	|		|		|		|		|
> |	PGCN	|	ICCV-2019	|	69.5	|	67.8	|	63.6	|	57.8	|	49.1	|	-	|	-	|	42.9	|	28.14	|	2.47	|	26.99	|		|		|		|		|
> |	C-TCN	|	arXiv	|	72.2	|	71.4	|	68	|	62.3	|	52.1	|	-	|	-	|	47.6	|	31.9	|	6.2	|	31.1	|		|		|		|			|
> |	G-TAD	|	arXiv	|	-	|	-	|	54.5	|	47.6	|	40.2	|	30.8	|	23.4	|	50.36	|	34.6	|	9.02	|	34.09	|		|		|			|		|
> |	CMCS	|	CVPR-2019	|	57.4	|	50.8	|	41.2	|	32.1	|	23.1	|	15	|	7	|	34	|	20.9	|	5.7	|	21.2	|	36.8	|	22	|	5.6	|	22.4	|
> |	STAR	|	AAAI-2019	|	68.8	|	60	|	48.7	|	34.7	|	23	|	-	|	-	|	31.1	|	18.8	|	4.7	|	-	|	31.1	|	18.8	|	4.7	|	-	|
> |	CleanNet	|	ICCV-2019	|	68.8	|	60	|	37	|	30.9	|	23.9	|	13.9	|	7.1	|		|		|		|		|	37.1	|	20.3	|	5	|	21.6	|
> |	TSM	|	ICCV-2019	|	-	|	-	|	39.5	|	-	|	24.5	|	-	|	7.1	|	30.3	|	19	|	4.5	|	-	|	28.3	|	17	|	3.5	|	-	|
> |	IWO-Net	|	TIP-2019	|	57.6	|	48.9	|	38.9	|	29.3	|	20.5	|	-	|	-	|	29.8	|	17.6	|	4.7	|	-	|		|		|	|		|
> |	BM	|	ICCV-2019	|	60.4	|	56	|	46.6	|	37.5	|	26.8	|	17.6	|	9	|	36.4	|	19.2	|	2.9	|	-	|		|		|		|		|
> |	Action-Search	|	ECCV-2018	|	-	|	-	|	51.8	|	42.4	|	30.8	|	20.2	|	11.1	|		|		|		|		|		|	|			|		|
> |	BSN	|	ECCV-2018	|	-	|	-	|	53.5	|	45	|	36.9	|	28.4	|	20	|	46.45	|	29.96	|	8.02	|	30.03	|		|		|		|		|
> |	TPC	|	AAAI-2018	|	-	|	-	|	44.1	|	37.1	|	28.2	|	20.6	|	12.7	| `` |		|		|		|		|		|		|		|
> |	Self-Ad	|	AAAI-2018	|	-	|	-	|	-	|	-	|	27.7	|	-	|	-	|		|		|		|		|		|		|		|		|
> |	One-Shot	|	CVPR-2018	|	-	|	-	|	-	|	-	|	14.7	|	-	|	-	|		|		|		|		|		|		|		|		|
> |	STPN	|	CVPR-2018	|	52	|	44.7	|	35.5	|	25.8	|	16.9	|	9.9	|	4.3	|	29.3	|	16.9	|	2.6	|	20.07	|		|		|		|		|
> |	AutoLoc	|	ECCV-2018	|	-	|	-	|	35.8	|	29	|	21.2	|	13.4	|	5.8	|		|		|		|		|	27.3	|	15.1	|	3.3	|	-	|
> |	W-TALC	|	ECCV-2018	|	55.2	|	49.6	|	40.1	|	31.1	|	22.8	|	-	|	7.6	|		|		|		|		|	37	|	-	|	-	|	18	|
> |	UNet	|	CVPR-2017	|	44.4	|	37.7	|	28.2	|	21.1	|	13.7	|	-	|	-	|		|		|		|		|	7.4	|	3.2	|	0.7	|	-	|
> |	H&S	|	ICCV-2017	|	36.44	|	27.84	|	19.49	|	12.66	|	6.84	|	-	|	-	|		|		|		|		|		|		|		|		|
> |	CDC	|	CVPR-2017	|	-	|	-	|	40.1	|	29.4	|	23.3	|	13.1	|	7.9	|	45.3	|	26	|	0.2	|	23.8	|		|		|		|		|
> |	SMS	|	CVPR-2017	|	51	|	45.2	|	36.5	|	27.8	|	17.8	|	-	|	-	|		|		|		|		|		|		|		|		|
> |	SSN	|	ICCV-2017	|	66	|	59.4	|	51.9	|	41	|	29.8	|	-	|	-	|	43.26	|	28.7	|	5.63	|	28.28	|		|		|		|		|
> |	R-C3D	|	ICCV-2017	|	54.5	|	51.5	|	44.8	|	35.6	|	28.9	|	-	|	-	|	26.8	|	-	|	-	|	-	|		|		|		|		|
> |	TCN	|	ICCV-2017	|	-	|	-	|	-	|	33.3	|	25.6	|	15.9	|	9	|	37.49	|	23.47	|	4.47	|	23.58	|		|		|		|		|
> |	TURN	|	ICCV-2017	|	54	|	50.9	|	44.1	|	34.9	|	25.6	|	-	|	-	|		|		|		|		|		|		|		|		|
> |	SST	|	ICCV-2017	|	-	|	-	|	-	|	-	|	23	|	-	|	-	|		|		|		|		|		|		|		|		|
> |	SCC	|	CVPR-2017	|		|		|		|		|		|		|		|	39.9	|	18.7	|	4.7	|	19.3	|		|		|		|		|
> |	FG	|	CVPR-2016	|	48.9	|	44	|	36	|	26.4	|	17.1	|	-	|	-	|		|		|		|		|		|		|		|		|
> |	PSDF	|	CVPR-2016	|	51.4	|	42.6	|	33.6	|	26.1	|	18.8	|	-	|	-	|		|		|		|		|		|		|		|		|
> |	SLM	|	CVPR-2016	|	39.7	|	35.7	|	30	|	23.2	|	15.2	|	-	|	-	|		|		|		|		|		|		|		|		|
> |	S-CNN	|	CVPR-2016	|	47.7	|	43.5	|	36.3	|	28.7	|	19	|	10.3	|	5.3	|		|		|		|		|		|		|		|		|
> |	DAPs	|	ECCV-2016	|	-	|	-	|	-	|	-	|	13.9	|	-	|	-	|		|		|		|		|		|		|		|		|

