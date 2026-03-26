# params 
 {'predict_dates': [{'start': '2026-03-26', 'end': '2026-03-26'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260326_16 587531851835566677 (Recorders: 1/5)

	Recorder: b9c7d2224ad54869801e271835b162ce

		Model: {'id': 'b9c7d2224ad54869801e271835b162ce', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.391, 'Rank IC': 0.057, 'Rank ICIR': 0.482}, 'data_train_vec': ['2024-03-26', '2025-09-25'], 'train_time_vec': ['2026-03-26', '2026-03-26']}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260326_14 108872783346882177 (Recorders: 1/5)

	Recorder: c9838e3c9b9e46a08aeaa92eba95d789

		Model: {'id': 'c9838e3c9b9e46a08aeaa92eba95d789', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.341, 'Rank IC': 0.047, 'Rank ICIR': 0.391}, 'data_train_vec': ['2024-03-26', '2025-09-25'], 'train_time_vec': ['2026-03-26', '2026-03-26']}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260326_13 353716569959617055 (Recorders: 1/5)

	Recorder: 298fbf5c18214deab17ce67384d335c3

		Model: {'id': '298fbf5c18214deab17ce67384d335c3', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.257, 'Rank IC': 0.046, 'Rank ICIR': 0.514}, 'data_train_vec': ['2025-03-26', '2025-12-25'], 'train_time_vec': ['2026-03-26', '2026-03-26']}
