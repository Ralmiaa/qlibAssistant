# params 
 {'predict_dates': [{'start': '2026-05-21', 'end': '2026-05-21'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260521_15 680421608773660591 (Recorders: 1/5)

	Recorder: fbc7ee88f8c047508bf0af193faca1b4

		Model: {'id': 'fbc7ee88f8c047508bf0af193faca1b4', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.044, 'ICIR': 0.307, 'Rank IC': 0.028, 'Rank ICIR': 0.201}, 'data_train_vec': ['2025-05-21', '2026-02-20'], 'train_time_vec': ['2026-05-21', '2026-05-21']}
