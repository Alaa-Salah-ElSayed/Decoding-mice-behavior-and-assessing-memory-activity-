# Decoding-mice-behavior-and-assessing-memory-activity
It is training project that I did in [Imbizo](https://github.com/isicnimbizo).I tried to decode the mice behavior based on performing a two-alternative forced choice (2AFC) task using the Steinmetz dataset.

# By going in 2 domains assessing :

  1- Neural activity :
  
         1) Relationship between firing rates (in brain regions) and visual conditions
         2) Relationship between firing rates (in brain regions) and response type
         3) Asessing the correct  vs incorrect trials by PCA
          
      
  2- Memory activity
          
          Build linear decoder (MLP) to assess the memory activity in relation to relative information using:
          Delayed period + average brain activity ( input) to predict stimulus location(output)
          
 # Challenges and lessons learned
   * The input (delayed period and average brain activity ) does not have the same dimensions (maybe data need more cleaning)
   
