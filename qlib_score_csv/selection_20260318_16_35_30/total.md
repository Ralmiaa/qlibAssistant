# params 
 {'predict_dates': [{'start': '2026-03-18', 'end': '2026-03-18'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260318_16 322679288670599288 (Recorders: 1/5)

	Recorder: 09adc2ffc018477c81e0a86d655e9255

		Model: {'id': '09adc2ffc018477c81e0a86d655e9255', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.262, 'Rank IC': 0.046, 'Rank ICIR': 0.346}, 'data_train_vec': ['2024-03-18', '2025-09-17'], 'train_time_vec': ['2026-03-18', '2026-03-18']}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260318_14 488068632394936752 (Recorders: 1/5)

	Recorder: 9ed83e345dd34945b28693b70360d5e4

		Model: {'id': '9ed83e345dd34945b28693b70360d5e4', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.311, 'Rank IC': 0.037, 'Rank ICIR': 0.353}, 'data_train_vec': ['2024-03-18', '2025-09-17'], 'train_time_vec': ['2026-03-18', '2026-03-18']}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260318_13 223299504910196561 (Recorders: 1/5)

	Recorder: 9a2d8cf143214b13a3ea3426e5ccd771

		Model: {'id': '9a2d8cf143214b13a3ea3426e5ccd771', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.315, 'Rank IC': 0.054, 'Rank ICIR': 0.502}, 'data_train_vec': ['2025-03-18', '2025-12-17'], 'train_time_vec': ['2026-03-18', '2026-03-18']}
