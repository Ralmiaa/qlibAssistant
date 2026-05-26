# params 
 {'predict_dates': [{'start': '2026-05-26', 'end': '2026-05-26'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260526_18 427041378481995762 (Recorders: 1/5)

	Recorder: ab63c9584df34ede895dae458365dffa

		Model: {'id': 'ab63c9584df34ede895dae458365dffa', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.085, 'ICIR': 0.451, 'Rank IC': 0.045, 'Rank ICIR': 0.217}, 'data_train_vec': ['2025-05-26', '2026-02-25'], 'train_time_vec': ['2026-05-26', '2026-05-26']}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260526_16 574515316593633387 (Recorders: 1/5)

	Recorder: f62bed45aecc40bdb6775a8877c89bdd

		Model: {'id': 'f62bed45aecc40bdb6775a8877c89bdd', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.052, 'ICIR': 0.302, 'Rank IC': 0.038, 'Rank ICIR': 0.255}, 'data_train_vec': ['2025-05-26', '2026-02-25'], 'train_time_vec': ['2026-05-26', '2026-05-26']}
