# params 
 {'predict_dates': [{'start': '2026-05-18', 'end': '2026-05-18'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260518_17 892348660662934085 (Recorders: 1/5)

	Recorder: da18e777d7374692b0024e75e07fb182

		Model: {'id': 'da18e777d7374692b0024e75e07fb182', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.095, 'ICIR': 0.595, 'Rank IC': 0.048, 'Rank ICIR': 0.277}, 'data_train_vec': ['2025-05-18', '2026-02-17'], 'train_time_vec': ['2026-05-18', '2026-05-18']}
