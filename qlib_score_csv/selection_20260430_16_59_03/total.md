# params 
 {'predict_dates': [{'start': '2026-04-30', 'end': '2026-04-30'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260430_16 913167942848073907 (Recorders: 1/5)

	Recorder: efeb0944314744bba8fdda871d35ecf5

		Model: {'id': 'efeb0944314744bba8fdda871d35ecf5', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.075, 'ICIR': 0.643, 'Rank IC': 0.035, 'Rank ICIR': 0.287}, 'data_train_vec': ['2025-04-30', '2026-01-29'], 'train_time_vec': ['2026-04-30', '2026-04-30']}
