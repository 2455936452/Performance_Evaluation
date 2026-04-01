# Performance_Evaluation
主动股票型基金超额收益相关研究

## 项目简介
本项目中文件仅为了复现论文Performance Evaluation, Factor Models, and Portfolio Strategies: Evidence from Chinese Mutual Funds (Yeguang Chi, Yu Liu, Xiao Qiao, working paper / conference paper, 2022)

先设置config（主要是设置为自己的tushare的token，要求至少2000积分）
按照0_get_fund -> 0_get_index (-> name_clear) -> *1_get_funds -> 2_get_label -> 3_make_25per -> 3_CAPM -> *4_fama_french -> 4_CAPM_ff3，顺序即可
其中星号代表会跑大量数据
