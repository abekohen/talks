- About me
- About jupyter
    - jupyter lab
    - code cell & history
    - magic, !, ?, ??
    - markdown (Euler said: $e^{i\pi}+1=0$)
- stocks.csv
    - first contact with data
    - pd.read_csv
    - df.memory_usage()
    - df.columns
    - len(df)
    - df.dtypes
    - read with parse_dates
    - df['Symbol']  # column is pd.Series
    - df['Symbol'] == 'AAPL'
    - df[df['Symbol'] == 'AAPL']
    - df[(df['Symbol'] == 'AAPL') & (df['Volume'] > 30)]
    - mask = (df['Symbol'] == 'AAPL') & (df['Volume'] > 30)
    - df[~mask]
    - df[5:8]
    - df[6]  # error
    - df.loc[6]
    - df['Volume'] * df['Price']
    - (df['Volume'] * df['Price']).sum()
    - df['Symbol'].value_counts()
    - df.groupby('Symbol')['Price'].median()
    - %matplotlib inline
    - (df['Volume'] * df['Price']).plot.bar()
    - df.index = df['Date'].dt.date
    - (df['Volume'] * df['Price']).plot.bar(rot=45)
    - df.loc[3] # error	
    - df.iloc[3]
- taxi.py
    - First contact - how much memory it'll take? read 1000 lines
    - exercises...
