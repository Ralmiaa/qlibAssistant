# params 
 {'predict_dates': [{'start': '2026-05-14', 'end': '2026-05-14'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260514_17 166067295882463621 (Recorders: 1/5)

	Recorder: 2ea6284ad6444e0eaad6923060db9540

		Model: {'id': '2ea6284ad6444e0eaad6923060db9540', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.095, 'ICIR': 0.639, 'Rank IC': 0.046, 'Rank ICIR': 0.304}, 'data_train_vec': ['2025-05-14', '2026-02-13'], 'train_time_vec': ['2026-05-14', '2026-05-14']}
