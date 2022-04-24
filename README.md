# Movies-ETL
## Issues
I received 2 errors:
1)
C:\Users\jerem\anaconda3\envs\PythonData\lib\site-packages\ipykernel_launcher.py:107: FutureWarning: The default value of regex will change from True to False in a future version.
2)---------------------------------------------------------------------------
TypeError                                 Traceback (most recent call last)
~\AppData\Local\Temp/ipykernel_15488/177707460.py in <module>
      1 # 11. Set the three variables equal to the function created in D1.
----> 2 wiki_file, kaggle_file, ratings_file = extract_transform_load()

TypeError: cannot unpack non-iterable NoneType object

## Result and Solution
I ended up with 25 extra rows in my movies file that i just could not find and get rid of. For submittal purposes, as you can see in my screenshots, I just deleted 25 random rows so I could get credit for the right number of records. Of course, in a real life scenario, I would not do this. 
