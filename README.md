# Infocepts-Data-Engineering-Hackathon

Tasks are as follows:
1. Process the "start_time_ts" column to create "time_spec_points" column. Allot exact points equaling the time of the day the user is surfing, but allot extra 5 points if they are surfing after 4 o clock in the afternoon. For example: If the user starts surfing at 9 o clock in the morning allot 9 points, but user surfing after 4 o clock in the afternoon will receive 21 points.
2. Reduce the "total_duration" round to 2 decimal places: example (166.711175 -> 166.71) (0.935320 -> 0.94)
3.  Add the values of columns  "total_clicks", "total_items", "total_cats" to create a new column: "total_inventory". If the value "total_inventory" is greater than 10, then make sure the value is increased by 100%.
4. Create a new column "give_big_discount". The value of '"give_big_discount" should be 1 if day_of_week is 0 and is_special_day is 1, otherwise 0.
5. Create a new column prod_views_buys_ratio which should be a ratio of prod_views_freqs and prod_buys_freqs
6. Create a new column create loyalty_points which should be calculated based on the following conditions: if a user is spending more than 3 seconds on a Sunday -- and loyalty points score will be 10 multiplied seconds over 3. 
7. Check the submission file for column details.
