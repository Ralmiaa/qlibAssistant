# params 
 {'predict_dates': [{'start': '2026-04-10', 'end': '2026-04-10'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260410_16 245749383660071435 (Recorders: 1/5)

	Recorder: e969d91b47c74242bbebb61152279648

		Model: {'id': 'e969d91b47c74242bbebb61152279648', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.326, 'Rank IC': 0.044, 'Rank ICIR': 0.391}, 'data_train_vec': ['2024-04-10', '2025-10-09'], 'train_time_vec': ['2026-04-10', '2026-04-10']}
