# params 
 {'predict_dates': [{'start': '2026-03-20', 'end': '2026-03-20'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260320_13 229056087845659391 (Recorders: 1/5)

	Recorder: c5f969c7ad3848c39096e3066e40a4a0

		Model: {'id': 'c5f969c7ad3848c39096e3066e40a4a0', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.328, 'Rank IC': 0.04, 'Rank ICIR': 0.366}, 'data_train_vec': ['2024-03-20', '2025-09-19'], 'train_time_vec': ['2026-03-20', '2026-03-20']}
