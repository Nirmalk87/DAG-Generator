# DAG-Generator
Random Directed Acyclic Graph (DAG) Generator


• Reference: H. Topcuoglu, S. Hariri, and M. Wu, “Performance-Effective and Low-Complexity Task Scheduling for Heterogeneous   Computing,” IEEE Trans. Parallel and Distributed Systems, vol. 13, no. 3, pp. 260-274, Mar. 2002

• Dependencies:  
	1.Tool  dependencies:  Python  2.7.6,  graphviz (optional graph visulization package)  
	2.Python  packages  dependencies:  numpy,  random,  copy,  csv,  graphviz   (optional graph visulization package)
	
• Run command:  "python graph_gen.py"

• Hard  coded  input  file: "graph.config" 

• Script  output  files:  
	1.graph_plot.gv.pdf :  DAG  image  
	2.resource_BW.csv:  Communication  bandwidth  among  processors  
	3.task_connectivity.csv: Edges  and  their  weight  (data  size)  among  DAG  nodes  
	4.task_exe_time.csv: Execution  time  of  each  task  on  different  processors 

• "graph.config": Input configuration file for selecting graph structure, node weights (computation time) and edge weights (communication time).
