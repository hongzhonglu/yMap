# yMap

yMap is a python based fast and robust automated method to map large yeast variants to 
            
            - proteins post-translational modifications 
                            
            - proteins domains, 
                            
            - proteins-DNA binding domains, 
                        
            - proteins structural regions, 
                
            - proteins active and binding sites 
                
            - proteins networks visualisation. 


The post-translational modifications in yMap are collected from different repositories like UniProt and sources 
with annotated PTMs like PTMcode 2.0 and PTMfunc, for more details, see README file.

In a user friendly way, it generates a "final-report" file to report all the non-synonymous 
mutations that overlaps or falls inside the above mentioned proteins functional regions.
The final-report is complemented with two other files; enrichment and visualsation id file. 


#Contents

            scripts: ymap.py

            README: Introduction and details of functions/methods and data with a Manual - with details of how to run yMap 

            Supported data: data/PTMcode + PTMfunc

            Example data: examples mutations files




#Dependencies 
   
    yMap depends on:
            
            python 2.7.10
            
            Orange bioinformatics (http://pythonhosted.org/Orange-Bioinformatics/#installation)
            
    


#Usage
    
            os.chdir(../yMap)
            import ymap
            from ymap import *
            data()
            mutation_types_file()
            ymap()
        
        
#Documentation     
    
    For complete instructions see README file

    

This work in supported by KU Leuven. 
