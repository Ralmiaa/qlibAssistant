# params 
 {'predict_dates': [{'start': '2026-03-19', 'end': '2026-03-19'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260319_13 813380916161862590 (Recorders: 1/5)

	Recorder: 7d63232be9694c51a4a88eec75f0e5f8

		Model: {'id': '7d63232be9694c51a4a88eec75f0e5f8', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.276, 'Rank IC': 0.034, 'Rank ICIR': 0.308}, 'data_train_vec': ['2024-03-19', '2025-09-18'], 'train_time_vec': ['2026-03-19', '2026-03-19']}
