# params 
 {'predict_dates': [{'start': '2026-04-07', 'end': '2026-04-07'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260407_16 371727270710960051 (Recorders: 1/5)

	Recorder: 4216e1d533bb4f408e31dd00520d8a4e

		Model: {'id': '4216e1d533bb4f408e31dd00520d8a4e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.302, 'Rank IC': 0.037, 'Rank ICIR': 0.312}, 'data_train_vec': ['2024-04-07', '2025-10-06'], 'train_time_vec': ['2026-04-07', '2026-04-07']}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260407_14 670508256092455631 (Recorders: 1/5)

	Recorder: eefeb6319b5f4d9c88f432a9b980e494

		Model: {'id': 'eefeb6319b5f4d9c88f432a9b980e494', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.346, 'Rank IC': 0.036, 'Rank ICIR': 0.326}, 'data_train_vec': ['2024-04-07', '2025-10-06'], 'train_time_vec': ['2026-04-07', '2026-04-07']}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260407_13 726779038191724326 (Recorders: 1/5)

	Recorder: 0ed795681f844aeea0d4e72ca3258d67

		Model: {'id': '0ed795681f844aeea0d4e72ca3258d67', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.287, 'Rank IC': 0.032, 'Rank ICIR': 0.273}, 'data_train_vec': ['2024-04-07', '2025-10-06'], 'train_time_vec': ['2026-04-07', '2026-04-07']}
