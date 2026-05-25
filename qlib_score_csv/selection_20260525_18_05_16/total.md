# params 
 {'predict_dates': [{'start': '2026-05-25', 'end': '2026-05-25'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260525_17 663922413121741506 (Recorders: 1/5)

	Recorder: 2dcf4baf192b4b6982f5e426ab651c92

		Model: {'id': '2dcf4baf192b4b6982f5e426ab651c92', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.095, 'ICIR': 0.536, 'Rank IC': 0.052, 'Rank ICIR': 0.273}, 'data_train_vec': ['2025-05-25', '2026-02-24'], 'train_time_vec': ['2026-05-25', '2026-05-25']}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260525_15 120338732165121541 (Recorders: 1/5)

	Recorder: d6a82acf003d496094ff6fb6a841b386

		Model: {'id': 'd6a82acf003d496094ff6fb6a841b386', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.08, 'ICIR': 0.416, 'Rank IC': 0.053, 'Rank ICIR': 0.283}, 'data_train_vec': ['2025-05-25', '2026-02-24'], 'train_time_vec': ['2026-05-25', '2026-05-25']}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260525_15 573653237228284505 (Recorders: 1/5)

	Recorder: 9e8d4fb011764cf886a7202d65eef667

		Model: {'id': '9e8d4fb011764cf886a7202d65eef667', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.059, 'ICIR': 0.32, 'Rank IC': 0.042, 'Rank ICIR': 0.295}, 'data_train_vec': ['2025-05-25', '2026-02-24'], 'train_time_vec': ['2026-05-25', '2026-05-25']}
