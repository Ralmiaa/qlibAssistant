# params 
 {'predict_dates': [{'start': '2026-04-29', 'end': '2026-04-29'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260429_16 295966517035426347 (Recorders: 1/5)

	Recorder: 4bae14a787b04a919b1accf015ac3bda

		Model: {'id': '4bae14a787b04a919b1accf015ac3bda', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.063, 'ICIR': 0.543, 'Rank IC': 0.031, 'Rank ICIR': 0.232}, 'data_train_vec': ['2025-04-29', '2026-01-28'], 'train_time_vec': ['2026-04-29', '2026-04-29']}
