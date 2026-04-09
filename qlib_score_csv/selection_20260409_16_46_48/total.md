# params 
 {'predict_dates': [{'start': '2026-04-09', 'end': '2026-04-09'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260409_16 660832938493731458 (Recorders: 1/5)

	Recorder: 2abfdb5c57864b09b6e7fcfb3cda7a0e

		Model: {'id': '2abfdb5c57864b09b6e7fcfb3cda7a0e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.251, 'Rank IC': 0.036, 'Rank ICIR': 0.313}, 'data_train_vec': ['2024-04-09', '2025-10-08'], 'train_time_vec': ['2026-04-09', '2026-04-09']}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260409_14 832060893438862658 (Recorders: 1/5)

	Recorder: 4b9ddae187c24c87a603e29480b4fb76

		Model: {'id': '4b9ddae187c24c87a603e29480b4fb76', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.298, 'Rank IC': 0.03, 'Rank ICIR': 0.282}, 'data_train_vec': ['2024-04-09', '2025-10-08'], 'train_time_vec': ['2026-04-09', '2026-04-09']}
