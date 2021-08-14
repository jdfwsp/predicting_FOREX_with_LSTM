Can Machine Learning be used to predict FOREX closing price?

Model chosen: LSTM

Data source: Fai

Data preparation:
    Import
    Set Date column as datetime format and set as index
    Drop na values
    Slice out all data before 2020 (model experiences Exploding gradient with any more data than that)

Evaluation method:
    Verify that loss is not 'nan' while training model
    Plot Real vs Predicted values to see if any similarity

Summary:
    Plots of model run on top 7 FOREX datasets (in Images folder)