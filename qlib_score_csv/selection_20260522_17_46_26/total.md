# params 
 {'predict_dates': [{'start': '2026-05-22', 'end': '2026-05-22'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260522_17 277250194865477997 (Recorders: 1/5)

	Recorder: 6581c6472362485abbcb17744014d4ca

		Model: {'id': '6581c6472362485abbcb17744014d4ca', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.096, 'ICIR': 0.536, 'Rank IC': 0.047, 'Rank ICIR': 0.252}, 'data_train_vec': ['2025-05-22', '2026-02-21'], 'train_time_vec': ['2026-05-22', '2026-05-22']}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260522_15 421317582220042749 (Recorders: 1/5)

	Recorder: 903b12bc9d75426390b387538b2f89c2

		Model: {'id': '903b12bc9d75426390b387538b2f89c2', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.081, 'ICIR': 0.462, 'Rank IC': 0.042, 'Rank ICIR': 0.222}, 'data_train_vec': ['2025-05-22', '2026-02-21'], 'train_time_vec': ['2026-05-22', '2026-05-22']}
