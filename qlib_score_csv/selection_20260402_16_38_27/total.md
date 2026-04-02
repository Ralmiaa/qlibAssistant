# params 
 {'predict_dates': [{'start': '2026-04-02', 'end': '2026-04-02'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'stock_list': ['SH601699', 'SH601318'], 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.02}, {'icir': 0.25}, {'rankic': 0.02}, {'rankicir': 0.2}]}



 # model info 

Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260402_14 243456560216597129 (Recorders: 1/5)

	Recorder: ae164f7fd06f42409ba0993c99e80686

		Model: {'id': 'ae164f7fd06f42409ba0993c99e80686', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.251, 'Rank IC': 0.038, 'Rank ICIR': 0.364}, 'data_train_vec': ['2024-04-02', '2025-10-01'], 'train_time_vec': ['2026-04-02', '2026-04-02']}
