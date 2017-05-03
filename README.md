
# Adabas and Natural programming tutorial 
![alt text](https://cloud.githubusercontent.com/assets/25740455/25524035/259ecbf2-2c09-11e7-877b-585666f26d3f.png)

## Adabas

Short for "Adabtable Database"-- Adabas is the Comprehensive and scalable enterprise database management system optimized for big data and designed for reliability and high performance. Available for mainframe, Linux®, UNIX® and Windows® (LUW) platforms.

http://www2.softwareag.com/corporate/products/adabas_natural/adabas/default.aspx


## Natural programming language

Application development and deployment environment known for ease of-use, cross-platform portability and developer productivity. Available for mainframe, Linux®, UNIX® and Windows® (LUW) platforms.

http://www2.softwareag.com/corporate/products/adabas_natural/natural/default.aspx


## Hello World ! in Natural
~~Upload the video tutorial~~
### Check the video tutorials
 * Video file attached with this github page

#### To tryout yourself 
 * Download the Virtual machine image file from the TECHcommunity website (~~URL~~)
 * Run the 'Adabas and Natural' cheatsheets from Help menu
 * The 3 scenarios discussed here, in understanding of the Natural programming language are...
 
    - Hello World
      * Description : One of the many ways you can print your text/results on the console is through the usage of the WRITE "string" statement
    - Conditional constructs
      * Description : The DECIDE ON statement is used to specify multiple actions to be performed depending on the value (or values) contained in a variable. Here, the FIRST keyword indicates that only the first value is to be processed with the NUMVALUE variable being initialised to 10. And therefore, based on the value contained in the NUMVALUE, an appropriate message is to be printed on the console, which is achieved through the usage of the DISPLAY statement here.
        
    - Basic Array manipulation
      * Description : This program illustrates the usage of the definition, initialisation, copy-to-another-array and print to the console operations.
         * Definition and initialisation of three 2-dimentional arrays.
         * Movement of the data from one array into another.
         * Two approaches to print the whole of the 2-dimensional arrays onto the console:
            * through nested loop
            * without the usage of the nested loop
        
   - For Adabas : Retrieval of data from the database and print it on the screen
       * You would need to first, compile the data definition module CRUISE.NSD which contains the data fields 
       * The main program HISTOPGM.NSP would compute the total number of records in the Adabas file CRUISE for a specific START-HARBOR
       * Usage of REPEAT statement to initiate a processing loop, the exit condition for the loop would be a blank value for the START-HARBOR
       * Usage of ESCAPE statement to interrupt the linear flow of execution and exit the loop
 
### To explore more code samples....
  http://techcommunity.softwareag.com/ecosystem/communities/public/adanat/products/natural/codesamples/
 
### System Environment Requirement

 * Internet access
 * Windows 7 or higher
 * Adabas and Software AG designer (modules) pre-installed (provided as VM image)
 
  

### If You Find Issues
Please report through an email to UniversityRelations@softwareag.com


### Notice
This tutorial only serves the purpose of introducing the concept of Adabas and Natural at a basic level of understanding


### Notice for updating tutorial html files
Please do NOT modify files here, if you are not authorized to.
