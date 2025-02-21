# SQL Generation

Generate SQLs that satisfy target cost or cardinality constraints. 

(1) Generate target point queries (cardinality=1000):

	 python3 cal_time.py tpch card point 1000 1000
	 
	 

(2) Generate target range queries (cost in [1000, 2000]):

	python3 cal_time.py tpch cost range 1000 1000 2000


 Check the RL-based method at [https://github.com/TsinghuaDatabaseGroup/AI4DBCode/tree/master/SQLGen/code](https://github.com/TsinghuaDatabaseGroup/AI4DBCode/tree/master/SQLGen/code).
 
