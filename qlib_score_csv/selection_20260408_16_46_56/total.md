# params 
 {'predict_dates': [{'start': '2026-04-08', 'end': '2026-04-08'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260408_16 510089762539426593 (Recorders: 1/5)

	Recorder: f7a2c30ab83745afaa4b50a7d1a4e0f8

		Model: {'id': 'f7a2c30ab83745afaa4b50a7d1a4e0f8', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.322, 'Rank IC': 0.037, 'Rank ICIR': 0.311}, 'data_train_vec': ['2024-04-08', '2025-10-07'], 'train_time_vec': ['2026-04-08', '2026-04-08']}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260408_14 515160542858973237 (Recorders: 1/5)

	Recorder: d7c6074fe9334c5fa3790f178d8b36ed

		Model: {'id': 'd7c6074fe9334c5fa3790f178d8b36ed', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.317, 'Rank IC': 0.035, 'Rank ICIR': 0.343}, 'data_train_vec': ['2024-04-08', '2025-10-07'], 'train_time_vec': ['2026-04-08', '2026-04-08']}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260408_13 190177979808078927 (Recorders: 1/5)

	Recorder: db69e2c872d444f18b58478652f44874

		Model: {'id': 'db69e2c872d444f18b58478652f44874', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.301, 'Rank IC': 0.031, 'Rank ICIR': 0.27}, 'data_train_vec': ['2024-04-08', '2025-10-07'], 'train_time_vec': ['2026-04-08', '2026-04-08']}
