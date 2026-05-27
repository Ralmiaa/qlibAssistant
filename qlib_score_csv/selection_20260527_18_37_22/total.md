# params 
 {'predict_dates': [{'start': '2026-05-27', 'end': '2026-05-27'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260527_18 576721645661105253 (Recorders: 1/5)

	Recorder: 715dc84daf904a2a951ab500378f1689

		Model: {'id': '715dc84daf904a2a951ab500378f1689', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.09, 'ICIR': 0.482, 'Rank IC': 0.047, 'Rank ICIR': 0.243}, 'data_train_vec': ['2025-05-27', '2026-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27']}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260527_16 584375614043479739 (Recorders: 1/5)

	Recorder: c47f3ed72b1b42b7962249d81d381dd9

		Model: {'id': 'c47f3ed72b1b42b7962249d81d381dd9', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.052, 'ICIR': 0.314, 'Rank IC': 0.042, 'Rank ICIR': 0.256}, 'data_train_vec': ['2025-05-27', '2026-02-26'], 'train_time_vec': ['2026-05-27', '2026-05-27']}
