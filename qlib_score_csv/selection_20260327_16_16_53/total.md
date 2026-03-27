# params 
 {'predict_dates': [{'start': '2026-03-27', 'end': '2026-03-27'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260327_16 279257722645841988 (Recorders: 1/5)

	Recorder: 8bc9f538c3df4dd5ad9e13c25fef2701

		Model: {'id': '8bc9f538c3df4dd5ad9e13c25fef2701', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.285, 'Rank IC': 0.046, 'Rank ICIR': 0.36}, 'data_train_vec': ['2024-03-27', '2025-09-26'], 'train_time_vec': ['2026-03-27', '2026-03-27']}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260327_13 307085896974439422 (Recorders: 1/5)

	Recorder: 1ed6c5410a694dad8bd7f41b5614db3b

		Model: {'id': '1ed6c5410a694dad8bd7f41b5614db3b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.276, 'Rank IC': 0.036, 'Rank ICIR': 0.313}, 'data_train_vec': ['2024-03-27', '2025-09-26'], 'train_time_vec': ['2026-03-27', '2026-03-27']}
