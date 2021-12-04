# PatternMiner

This is a sample of the file names you can include in the location dict that you pass along as argument when you create objects.
The keys are the timestamp of the daily data of spot, future and option instruments. This location dictionary consists of the file paths of the banknifty instruments. 

spot = {'close':'C:\\Users\\geeta\\Desktop\\Data\\Data\\EOD\\EOD_NIFTY bank.pkl',
        '15:00':'C:\\Users\\geeta\\Desktop\\Data\\EOD-Data\\Data\\EOD\\resampled_banknifty_spot_data_15_00.pkl',
        '15:10':'C:\\Users\\geeta\\Desktop\\Data\\EOD-Data\\Data\\EOD\\resampled_banknifty_spot_data_15_10.pkl',
        '15:15':'C:\\Users\\geeta\\Desktop\\Data\\EOD-Data\\Data\\EOD\\resampled_banknifty_spot_data_15_15.pkl',
        '15:25':'C:\\Users\\geeta\\Desktop\\Data\\EOD-Data\\Data\\EOD\\resampled_banknifty_spot_data_15_25.pkl'}

future = {'close':'C:\\Users\\geeta\\Desktop\\EOD-spot-options\\banknifty_futures_data_current_expiry.pkl',
        '15:00':'C:\\Users\\geeta\\Desktop\\Data\\EOD-Data\\Data\\EOD\\resampled_banknifty_spot_data_15_00.pkl',
        '15:10':'C:\\Users\\geeta\\Desktop\\Data\\EOD-Data\\Data\\EOD\\resampled_banknifty_spot_data_15_10.pkl',
        '15:15':'C:\\Users\\geeta\\Desktop\\Data\\EOD-Data\\Data\\EOD\\resampled_banknifty_spot_data_15_15.pkl',
        '15:25':'C:\\Users\\geeta\\Desktop\\Data\\EOD-Data\\Data\\EOD\\resampled_banknifty_spot_data_15_25.pkl'}

option = {'close':'C:\\Users\\geeta\\Desktop\\Data\\EOD-Data\\Data\\EOD\\banknifty_options_data_no_dupl.pkl',
          '15:00':'C:\\Users\\geeta\\Desktop\\Data\\EOD-Data\\Data\\EOD\\resampled_banknifty_options_data_15_00.pkl',
          '15:10':'C:\\Users\\geeta\\Desktop\\Data\\EOD-Data\\Data\\EOD\\resampled_banknifty_options_data_15_10.pkl',
          '15:15':'C:\\Users\\geeta\\Desktop\\Data\\EOD-Data\\Data\\EOD\\resampled_banknifty_options_data_15_15.pkl',
          '15:25':'C:\\Users\\geeta\\Desktop\\Data\\EOD-Data\\Data\\EOD\\resampled_banknifty_options_data_15_25.pkl'}

location_dict = {'weekly':spot, 'monthly':future, 'option':option}


To create a daily pnl of any particular option strategy, you can choose the option strategy in the following format:

1) 
