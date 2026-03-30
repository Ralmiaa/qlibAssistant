# params 
 {'predict_dates': [{'start': '2026-03-30', 'end': '2026-03-30'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260330_16 664712482589192439 (Recorders: 1/5)

	Recorder: 6f80ce3d97594bcd94ec46bad41a886a

		Model: {'id': '6f80ce3d97594bcd94ec46bad41a886a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.312, 'Rank IC': 0.048, 'Rank ICIR': 0.366}, 'data_train_vec': ['2024-03-30', '2025-09-29'], 'train_time_vec': ['2026-03-30', '2026-03-30']}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260330_14 397811386519843987 (Recorders: 1/5)

	Recorder: 6a31ca9d72bb4d80858e8e7abf433845

		Model: {'id': '6a31ca9d72bb4d80858e8e7abf433845', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.037, 'ICIR': 0.358, 'Rank IC': 0.046, 'Rank ICIR': 0.411}, 'data_train_vec': ['2024-03-30', '2025-09-29'], 'train_time_vec': ['2026-03-30', '2026-03-30']}
