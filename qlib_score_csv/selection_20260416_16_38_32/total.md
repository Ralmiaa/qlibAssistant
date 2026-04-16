# params 
 {'predict_dates': [{'start': '2026-04-16', 'end': '2026-04-16'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260416_16 509463297340211994 (Recorders: 1/5)

	Recorder: 8f0b07ada49b4f3487a20f99c37aefb3

		Model: {'id': '8f0b07ada49b4f3487a20f99c37aefb3', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.041, 'ICIR': 0.305, 'Rank IC': 0.037, 'Rank ICIR': 0.245}, 'data_train_vec': ['2025-04-16', '2026-01-15'], 'train_time_vec': ['2026-04-16', '2026-04-16']}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260416_14 947608440602269878 (Recorders: 1/5)

	Recorder: b2cf797990a947b1bc8dbe341b557d7c

		Model: {'id': 'b2cf797990a947b1bc8dbe341b557d7c', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.26, 'Rank IC': 0.035, 'Rank ICIR': 0.244}, 'data_train_vec': ['2025-04-16', '2026-01-15'], 'train_time_vec': ['2026-04-16', '2026-04-16']}
