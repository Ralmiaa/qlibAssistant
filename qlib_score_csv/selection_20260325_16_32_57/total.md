# params 
 {'predict_dates': [{'start': '2026-03-25', 'end': '2026-03-25'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260325_16 279512685636028931 (Recorders: 1/5)

	Recorder: 872ee995408d4f2fb88aae6899c29d2a

		Model: {'id': '872ee995408d4f2fb88aae6899c29d2a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.352, 'Rank IC': 0.051, 'Rank ICIR': 0.441}, 'data_train_vec': ['2024-03-25', '2025-09-24'], 'train_time_vec': ['2026-03-25', '2026-03-25']}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260325_13 495490349777207553 (Recorders: 1/5)

	Recorder: c11cead02a664671a2efc99d6a1b3467

		Model: {'id': 'c11cead02a664671a2efc99d6a1b3467', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.389, 'Rank IC': 0.05, 'Rank ICIR': 0.445}, 'data_train_vec': ['2024-03-25', '2025-09-24'], 'train_time_vec': ['2026-03-25', '2026-03-25']}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260325_13 759388420413417409 (Recorders: 1/5)

	Recorder: 70aa04602be44171bbfe8de7fc11e803

		Model: {'id': '70aa04602be44171bbfe8de7fc11e803', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.252, 'Rank IC': 0.04, 'Rank ICIR': 0.556}, 'data_train_vec': ['2025-03-25', '2025-12-24'], 'train_time_vec': ['2026-03-25', '2026-03-25']}
