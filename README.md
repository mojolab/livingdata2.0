# livingdata2.0
New Improved Version of LivingData

## Major updates

1. This version of livingdata uses the Xetrapal automation framework (https://github.com/anandabhairav/xetrapal)
2. This version does not bother with defining tables etc, we use pandas instead. (https://pandas.pydata.org/)
3. Which means LivingData is now about workflows
.. 1. DataCube - A cube of DataFrames (such as the same table for multiple years as in a bank statement, or annual report)
.. 2. DataStream - A formatted dataset with a sliding window of the latest updates
