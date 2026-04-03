# params 
 {'predict_dates': [{'start': '2026-04-03', 'end': '2026-04-03'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260403_13 289978260396626814 (Recorders: 1/5)

	Recorder: a2a9b790204448279f92e5dcdd37d04d

		Model: {'id': 'a2a9b790204448279f92e5dcdd37d04d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.308, 'Rank IC': 0.036, 'Rank ICIR': 0.371}, 'data_train_vec': ['2024-04-03', '2025-10-02'], 'train_time_vec': ['2026-04-03', '2026-04-03']}
