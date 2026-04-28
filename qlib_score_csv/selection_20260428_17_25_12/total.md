# params 
 {'predict_dates': [{'start': '2026-04-28', 'end': '2026-04-28'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260428_17 922446378649194619 (Recorders: 1/5)

	Recorder: 4ac42f2bd63f46cf95c9e60be9360945

		Model: {'id': '4ac42f2bd63f46cf95c9e60be9360945', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.056, 'ICIR': 0.424, 'Rank IC': 0.03, 'Rank ICIR': 0.214}, 'data_train_vec': ['2025-04-28', '2026-01-27'], 'train_time_vec': ['2026-04-28', '2026-04-28']}
