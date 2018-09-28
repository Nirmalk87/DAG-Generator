# DAG-Generator
Random Directed Acyclic Graph (DAG) Generator


• Reference: H. Topcuoglu, S. Hariri, and M. Wu, “Performance-Effective and Low-Complexity Task Scheduling for Heterogeneous   Computing,” IEEE Trans. Parallel and Distributed Systems, vol. 13, no. 3, pp. 260-274, Mar. 2002

• Dependencies:  
	1.Tool  dependencies:  Python  2.7.6,  graphviz  
	2.Python  packages  dependencies:  numpy,  random,  copy,  csv,  graphviz  
	
• Run command:  "python graph_gen.py"

• Hard  coded  input  file: "graph.config" 

• Script  output  files:  
	1.graph_plot.gv.pdf :  DAG  image  
	2.resource_BW.csv:  Communication  bandwidth  among  processors  
	3.task_connectivity.csv: Edges  and  their  weight  (data  size)  among  DAG  nodes  
	4.task_exe_time.csv: Execution  time  of  each  task  on  different  processors 

• "graph.config": Input configuration file for setting seed, depth and other graph specific parameters as described below.
	#Resource count (RC 3)
	RC 3
	#graph height (GH 6) 
	GH 9
	#task count (TC 20)
	TC 35
	#average out_degree (AOD 2)
	AOD 4
	#communication to computation ratio (CCR 2.0)
	CCR 0.2
	#Heterogenity factor (HF 0.5)
	# 0 <= HF < 1
	HF 0.5
	#Communication data packet range (CDR 10 100)
	CDR 10 100
	#Link Bandwidth range (LBW 10 100)
	LBW 10 100
	#RANDOM seed value SEED
	SEED 9000
~           
