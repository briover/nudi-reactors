---
output:
  pdf_document: default
  html_document: default
---
# DS 2024: Nudi Reactors Repository
Raw data, data analysis and manipulation

Brianna Over, Luca Meyknecht and Fiona Parker



# nudi-reactors: Directed Study Group Repository

Welcome to the **nudi-reactors** repository: 

## Purpose
This repository will be used for storing and sharing data for our fall 2024 directed studies project at BMSC. our project looks into the effects of temperature on the chemosensory abilities of the nudibranch Hermissenda crassicornis. Throughout our study we use many different statistical analyses on R Studio, all of which will be found in this repository along with our graphs and tables. Information on our methods and results can be found in our paper *Temperature-induced shifts in chemosensory responses of Hermissenda crassicornis to predator and conspecific cues*


main analyses that were preformed were: 
a gamma model comparing nudibranch speed to temperature and body size 
a binomial model that compares nudibranch movement based on the chemical cue to temperature treatment and again body size. 


# Folders 

*a quick note* - most files will begin with Meyknecht_Over_Parker_MRNE475_2024_ this is to help with organization at BMSC this can be ignored, what is after this is the file name.

## tables - in this folder you will find the printed pngs of each table found in our paper as well as the data that was used to create them. 
    
   *velocity_model_table.png* this is the table that demonstrates the results 
    and significance of the velocity model.
   
   *model_binom_table.png* this is the table that demonstrates the results and 
    significance of the binomial model.
    
   *avgmean_vel_table.png* this is the table that demonstrates the mean average
    mean velocity per temperature group along with the standard error.
    
   *mean_vel.csv* this was the data used for the average mean velocity table
    
   *excel_velocity.xlsx* this was the file used for the velocity model table
    
   *binom_excel.xlsx* this was the data used to make thebinomial model table

## raw_data - in this folder you will find the raw data we collected and uploaded into R.
    
  *rawtrialdata.csv* this is the data that was directly collected in our 
    experiemental trials
    
   *rawpred.csv* this is the data that we got after running our trial results 
    thorugh Image J for the predators.
    
   *rawcons.csv* this is the data that we got after running our trial results 
    through Image J for the conspecific.
    
   *nudisizeraw* thsi is the data that we got from Image J with body size 
    information for thenudibranchs

## plots_circle - here you will find all he printed images of our angular direction graphs, these are not used in our paper but further description of them is found in fionas_scripts > Fiona's_graphs.
    
   *angular direction graphs* all these graphs show the average angular 
    direction for each nudibranch in its temperature trial. they are seperated 
    by conspecific and predator treatments. some have been shrunk down in size.
   
   *four_panel_plot_pred_resultssmall.png*
   *four_panel_plot_cons_resultssmall.png*
   *four_panel_plot_pred_results.png*
   *four_panel_plot_cons_results.png*

## luca_scripts - here you will find all the code and plots for the velocity model.
    
  *statistics_velocity.Rmd* this R file contains the process to getting the 
    gamma model for the velocity.
   
  *perfectplot.png* - boxplot of the mesn velocity for different treatment 
    groups + average of mean velocity. Plot we actually use in the paper.
    
  *nudi_gamma_factor_times_coefficients.csv*- exported gamma model summary 
    into csv table. This table was altered to use it in our table.
    
  *lm_length_vel2.png* - linear model mean vel and avg length with points and 
    error polygon, used in paper.
    
  *goodboxplot.png* - boxplot without the avg mean velocity, did not use this 
    one in the paper
    
  *boxplot_nudi.pdf* - same boxplot without avg mean vel: not used because it 
    is a pdf and not png
    
  *boxplot_jitter_nudi.pdf* - not used, boxplot with jitter, saved as pdf
    
  *clean_script_luca.rmd* this contains a clean and well annotated code for 
    the entire velocity model and all its graphs.inlcudes knit pdf

## Fiona_scripts - 
    
  *fionatables.Rmd* - here you will find the code for all the tables used in 
    the paper. incliudes knit pdf
    
  *Fiona's_graphs.Rmd* - here you will find all the code for the angular 
    direction plots.
   
  *fiona_models.Rmd* - here you will find all the code for creating 
    "combinedraw" a data set used in the models. includes knit pdf

## clean_data - here you will find all the data we cleaned in R Studio 
    
  *combinedraw.csv* - this is a common data set we use it contains mean values 
    and some raw data. 
   
  *combinedraw_no_spaces.csv* - this is the same data set however without the 
    space issue present in the first

## bri_code - here you will find all the code use to make and graph the binomial model in our paper.
    
  *plot_rxn_probs.png* - plots the proportion of nudibranchs that went 
     towards and away from cues for each treatment. 
   
   *binom_table.csv* - altered table of results from the binomial model
   
   *binom_table.xlsx* - sane table but excel format, used to make the table seen in the paper
  
   *nudireactors_bmodel_wgraphs.Rmd* - contains the clean code forthe binomial model and all the graphs, includes a knit pdf
  
   *reaction_binom_model.Rmd* - contains the process of getting the binomial model, not a clean code,includes a knit pdf
  
  all the following are part of the process for getting the mean angular direction graphs
   *pred_trials_individualanglecirc.Rmd*
   *pred_trials_anglegg.Rmd*
   *pred_trials_anglebar.Rmd*
   *pred_trials_anglecirc.Rmd*
   
   ## metadata - all the metadata is included in this folder 






