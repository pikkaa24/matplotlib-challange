# matplotlib-challange

Referenced https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.duplicated.html and https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.drop_duplicates.html#pandas.DataFrame.drop_duplicates for assistance on how to identify and drop duplicates

Referenced https://pandas.pydata.org/docs/getting_started/intro_tutorials/06_calculate_statistics.html for assistance on aggregation method of statistical summary.

Referenced following code tp retrieve greatest timepoint for each Mouse ID from Xpert Learning Assistant:
    # Assuming you have a DataFrame named df with columns 'Mouse ID' and 'Timepoint'

    # Group the DataFrame by 'Mouse ID' and find the maximum timepoint for each group
    max_timepoints = df.groupby('Mouse ID')['Timepoint'].max()

    # Print or display the maximum timepoint for each mouse ID
    print(max_timepoints)

Referenced https://matplotlib.org/ for ways to format different plots. 