# params 
 {'predict_dates': [{'start': '2026-05-08', 'end': '2026-05-08'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260508_14 893301482534851146 (Recorders: 1/5)

	Recorder: 758bfcc5e6d744f8b9baba0925faac57

		Model: {'id': '758bfcc5e6d744f8b9baba0925faac57', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.072, 'ICIR': 0.622, 'Rank IC': 0.042, 'Rank ICIR': 0.382}, 'data_train_vec': ['2025-05-08', '2026-02-07'], 'train_time_vec': ['2026-05-08', '2026-05-08']}
