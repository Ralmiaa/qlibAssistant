# params 
 {'predict_dates': [{'start': '2026-03-24', 'end': '2026-03-24'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260324_16 793589133122178279 (Recorders: 1/5)

	Recorder: 82c2919863c7462ca0b5729220fc6f61

		Model: {'id': '82c2919863c7462ca0b5729220fc6f61', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.348, 'Rank IC': 0.045, 'Rank ICIR': 0.413}, 'data_train_vec': ['2024-03-24', '2025-09-23'], 'train_time_vec': ['2026-03-24', '2026-03-24']}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260324_13 382342195245726819 (Recorders: 1/5)

	Recorder: aa133838cdfb40e2a35a51ade3e89e1a

		Model: {'id': 'aa133838cdfb40e2a35a51ade3e89e1a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.035, 'ICIR': 0.337, 'Rank IC': 0.045, 'Rank ICIR': 0.389}, 'data_train_vec': ['2024-03-24', '2025-09-23'], 'train_time_vec': ['2026-03-24', '2026-03-24']}
