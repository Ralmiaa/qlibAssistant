# params 
 {'predict_dates': [{'start': '2026-05-13', 'end': '2026-05-13'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260513_17 334960008360498577 (Recorders: 1/5)

	Recorder: a1aa7c24bf0c4fffb3f38bdbb01f6c5b

		Model: {'id': 'a1aa7c24bf0c4fffb3f38bdbb01f6c5b', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.097, 'ICIR': 0.678, 'Rank IC': 0.045, 'Rank ICIR': 0.325}, 'data_train_vec': ['2025-05-13', '2026-02-12'], 'train_time_vec': ['2026-05-13', '2026-05-13']}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260513_15 428170353017134228 (Recorders: 1/5)

	Recorder: 13d5c22ef8e843dc85f2427eb65ad18c

		Model: {'id': '13d5c22ef8e843dc85f2427eb65ad18c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.084, 'ICIR': 0.628, 'Rank IC': 0.04, 'Rank ICIR': 0.302}, 'data_train_vec': ['2025-05-13', '2026-02-12'], 'train_time_vec': ['2026-05-13', '2026-05-13']}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260513_14 574693180152661552 (Recorders: 1/5)

	Recorder: 0aeac39ef44b4b38a9fda8a6dbf81cdd

		Model: {'id': '0aeac39ef44b4b38a9fda8a6dbf81cdd', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.048, 'ICIR': 0.407, 'Rank IC': 0.022, 'Rank ICIR': 0.209}, 'data_train_vec': ['2025-05-13', '2026-02-12'], 'train_time_vec': ['2026-05-13', '2026-05-13']}
