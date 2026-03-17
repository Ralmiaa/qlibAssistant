# params 
 {'predict_dates': [{'start': '2026-03-17', 'end': '2026-03-17'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260317_13 277228208802943028 (Recorders: 2/5)

	Recorder: 83ebfd0508aa4d58ab4f2d4129033ac9

		Model: {'id': '83ebfd0508aa4d58ab4f2d4129033ac9', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.3, 'Rank IC': 0.037, 'Rank ICIR': 0.357}, 'data_train_vec': ['2024-03-17', '2025-09-16'], 'train_time_vec': ['2026-03-17', '2026-03-17']}

	Recorder: 4f838a7c356f4164acd3b061bc2e0810

		Model: {'id': '4f838a7c356f4164acd3b061bc2e0810', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.263, 'Rank IC': 0.07, 'Rank ICIR': 0.656}, 'data_train_vec': ['2025-03-17', '2025-12-16'], 'train_time_vec': ['2026-03-17', '2026-03-17']}
