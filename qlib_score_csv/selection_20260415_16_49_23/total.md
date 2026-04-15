# params 
 {'predict_dates': [{'start': '2026-04-14', 'end': '2026-04-14'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260415_16 201452864236733148 (Recorders: 1/5)

	Recorder: fc13f84808e949c5bc071ead2440216c

		Model: {'id': 'fc13f84808e949c5bc071ead2440216c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.28, 'Rank IC': 0.035, 'Rank ICIR': 0.219}, 'data_train_vec': ['2025-04-15', '2026-01-14'], 'train_time_vec': ['2026-04-15', '2026-04-15']}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260415_14 216081695100412517 (Recorders: 1/5)

	Recorder: 8a2eb24b42814384abcd8c74b653d0fb

		Model: {'id': '8a2eb24b42814384abcd8c74b653d0fb', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.044, 'ICIR': 0.251, 'Rank IC': 0.037, 'Rank ICIR': 0.208}, 'data_train_vec': ['2025-04-15', '2026-01-14'], 'train_time_vec': ['2026-04-15', '2026-04-15']}
