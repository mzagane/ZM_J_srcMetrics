# ZM_J_Code_Metrics
Tool to calculate code metrics based on the XML representation of the source code obtained by applying @srcML

1) Metrics that can be calculated in the actual version (1.06.06.2020)


1.1) LOC :
  - Total lines (physic lines),
  - lines of comments,
  - Blank lines
  
1.2) McCab Metrics :
  - McCab Number (cyclomatic complexity)
  
1.3) Halstead complexity metrics :
  - n1: Number of distinct operators
  - n2: Number of distinct operands  
  - N1: Total number of operators    
  - N2: Total number of operands     
  - n: Program vocabulary          
  - N: Program length               
  - N': Calculated program length   
  - V: Volume                      
  - D: Difficulty                   
  - E: Effort                      
  - T: Time Required To Program     
  - B1 :Number of delivered bugs    
  - B2 :Number of delivered bugs     
 
 
 2) Programming languages supported:
 
 The metrics are calculated from the XML representation generated by the srcML tool, therefore all languages supported
 by srcML can be supported by ZM J Code Metrics. The actual version works very fine with c/c++, a minors changes can be 
 done to support the others languages supported by srcML : java, c#, ...
 
 To calculate metrics, ZM Code Metrics must know some informations about the language such as list of key words, control 
 commands,... which are stored in a config file (property file). When trying to add a language this parameters must be taken
 in account (may be this is the most thing to do to add a language :)
 
 
