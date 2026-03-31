# params 
 {'predict_dates': [{'start': '2026-03-31', 'end': '2026-03-31'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260331_16 199737619411505127 (Recorders: 1/5)

	Recorder: eb6cca9d9ec2434fb7e1aabfc58f8f4f

		Model: {'id': 'eb6cca9d9ec2434fb7e1aabfc58f8f4f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.303, 'Rank IC': 0.051, 'Rank ICIR': 0.383}, 'data_train_vec': ['2024-03-30', '2025-09-29'], 'train_time_vec': ['2026-03-31', '2026-03-31']}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260331_14 771221488792060226 (Recorders: 1/5)

	Recorder: 143b4600ce7f4f008b2c903e24acdcbe

		Model: {'id': '143b4600ce7f4f008b2c903e24acdcbe', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.316, 'Rank IC': 0.04, 'Rank ICIR': 0.37}, 'data_train_vec': ['2024-03-30', '2025-09-29'], 'train_time_vec': ['2026-03-31', '2026-03-31']}
