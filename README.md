We developed a machine learning model to categorize financial transactions using XLNet, a powerful text classification model. The process starts by preparing a dataset with transaction descriptions and corresponding categories. We first categorize descriptions based on predefined keywords from a CSV file. If the model encounters an "UNKNOWN" category, it prompts the user to specify a new category, updates the keyword list, and retrains the model with the new data. This ensures the model learns and adapts to new categories over time. The final model accurately predicts transaction categories, helping automate the organization of financial data. The output is an updated Excel file with transaction descriptions and their assigned categories, streamlining the data classification process.