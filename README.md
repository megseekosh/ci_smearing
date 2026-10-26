# ci_smearing
Analysis to replicate "Effects of spectral smearing on speech understanding and masking release in simulated bilateral cochlear implants", *PLoS One, 18*(11), e0287728.

`results.Rmd` - RMarkdown to replicate results, generate report and figures, etc. 

`smearing_data.csv` - dataframe used to generate results and figures

`results.pdf` - generated report of results

Note (Oct 2026): corrected two transcription errors in smearing_data.csv against raw data file (P9 SV-SV dichotic run 2: 5.3→0.7; P11 NV-NV diotic run 3: 1→1.7). See CISimulation-bilateral-Smearing.csv rows 14–15 for the source of the P9 error. Table 1 for L48R48 dichotic was computed from the erroneous value and shifts slightly with this fix (M −2.96→−3.09, SD 3.88→3.67, range max 5.3→3.8); model coefficients change by ≤0.08 dB and no conclusions change. The 2022 conference abstract was computed from the correct value. The SRM dataframe in results.Rmd duplicates each participant-condition SRM value (once per masker-ear row), so the published Table 3 model slightly understated standard errors. Estimates and unadjusted statistics were unchanged. 


