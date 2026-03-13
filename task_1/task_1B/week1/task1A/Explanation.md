What I learned through this task

1. Different libraries like pandas and matplotlib. A LOT of new syntax and how to use different functionalities in these libraries. Some commands which i found out during this are:
df.isnull() = checks for missing values in columns . Gives true if a value is missing
str.lower(),str.replace(),str.strip() and other str functions
plt.tight_layout() = makes sure that axis labels or titles do not overlap. Keeps it clean

2. I learned about categorical encoding.
    It is a step in processing of data which converts non-numeric data (like text based) to numerical   formats so that they can be used in machine learning .
   1/0 encoding = Used when the text based data is split in two (like male female, true false, etc..) 
   One hot encoding = kind of like 1/0 encoding except this has multiple categories and all of them are     made into either 0s or 1s. It transforms variables into (sort of) vectors in the form           [0/1,0/1,0/1,1/0,1/0,0/1] by using all its categories .
   
 3. Scaling is very important for making the data ready for machine learning.
    ML models require scaling to see every feature uniformly. For example, if math_score ranges from 0     to   100 and another feature ranges from 0 to 1, the model will treat math_score as 100x more important simply because its numbers are larger. Minmax scaling shrinks every value from 0 to 1.

