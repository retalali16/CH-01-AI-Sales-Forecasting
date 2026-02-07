# **CH-01AI SALES FORECASTING **  

## **RUN STEPS**  
1. **Environment Setup**  
   - Ensure **Python >= 3.8** is installed.  
   - Open `RetalAshrafAli_CH_01_AI_Sales_Forecasting.ipynb` in **Jupyter Notebook** or **JupyterLab**.  
   - Execute **Cell 2** to install required dependencies:  
     ```
     pandas, numpy, scikit-learn, xgboost, openpyxl, matplotlib, seaborn, arabic-reshaper, python-bidi
     ```  

2. **Data Preparation**  
   - Place the input file `"AI Cosmetics (003).xlsx - Sheet1.csv"` in:  
     `C:\Input\`  
   - Verify **UTF-8 encoding**.  

3. **Notebook Execution**  
   - Run **all notebook cells sequentially (Cells 1–19)**.  
   - **Do not skip or reorder cells.**  
   - Monitor console for **data validation** messages.  

4. **Output Retrieval**  
   - Forecasts saved in `predictions.csv` in the **output directory**.  
   - Check console logs for **evaluation metrics** (MAE, RMSE, WAPE, sMAPE).  

## **EXPECTED RUNTIME**  

**Total execution time:** ~3–8 minutes  
(Dependent on dataset size and system hardware)  

**Estimated breakdown:**  
- Environment setup           : 30–60 sec  
- Data loading & validation    : 20–40 sec  
- Feature engineering         : 15–30 sec  
- Sales model training        : 45–90 sec  
- Quantity model training     : 45–90 sec  
- Forecast generation & export: 40–75 sec  

**Note:** Runtime scales linearly with **number of brand–location combinations**.  

## **HARDWARE ASSUMPTIONS**  

- **RAM:** Minimum 8 GB (16 GB recommended)  
- **CPU:** Modern multi-core processor for faster model training  
- **Disk:** Sufficient space for input CSV and output files (~50–100 MB typical)  
- Fully offline execution supported  
