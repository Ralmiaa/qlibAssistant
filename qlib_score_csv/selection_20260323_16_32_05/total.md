# params 
 {'predict_dates': [{'start': '2026-03-23', 'end': '2026-03-23'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260323_16 536906302068873023 (Recorders: 1/5)

	Recorder: 207cd13bb6e4435abdf39fa16f333270

		Model: {'id': '207cd13bb6e4435abdf39fa16f333270', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.268, 'Rank IC': 0.044, 'Rank ICIR': 0.383}, 'data_train_vec': ['2024-03-23', '2025-09-22'], 'train_time_vec': ['2026-03-23', '2026-03-23']}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260323_13 202627589177293766 (Recorders: 1/5)

	Recorder: 8c489106588149a99e7059fd0cbef995

		Model: {'id': '8c489106588149a99e7059fd0cbef995', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.252, 'Rank IC': 0.043, 'Rank ICIR': 0.367}, 'data_train_vec': ['2024-03-23', '2025-09-22'], 'train_time_vec': ['2026-03-23', '2026-03-23']}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260323_13 173805267612196665 (Recorders: 1/5)

	Recorder: 54f6d51af44b4da885b62294b0c0495b

		Model: {'id': '54f6d51af44b4da885b62294b0c0495b', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.251, 'Rank IC': 0.048, 'Rank ICIR': 0.454}, 'data_train_vec': ['2024-03-23', '2025-09-22'], 'train_time_vec': ['2026-03-23', '2026-03-23']}
