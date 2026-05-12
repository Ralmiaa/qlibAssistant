# params 
 {'predict_dates': [{'start': '2026-05-12', 'end': '2026-05-12'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260512_17 645300707196650841 (Recorders: 1/5)

	Recorder: 5ba1e913fa2f410498fec9426a1f785f

		Model: {'id': '5ba1e913fa2f410498fec9426a1f785f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.075, 'ICIR': 0.586, 'Rank IC': 0.024, 'Rank ICIR': 0.217}, 'data_train_vec': ['2025-05-12', '2026-02-11'], 'train_time_vec': ['2026-05-12', '2026-05-12']}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260512_14 266910975888161191 (Recorders: 1/5)

	Recorder: 6a8b2a84d5874a3fa7cc025fc10fc8ec

		Model: {'id': '6a8b2a84d5874a3fa7cc025fc10fc8ec', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.069, 'ICIR': 0.584, 'Rank IC': 0.024, 'Rank ICIR': 0.232}, 'data_train_vec': ['2025-05-12', '2026-02-11'], 'train_time_vec': ['2026-05-12', '2026-05-12']}
