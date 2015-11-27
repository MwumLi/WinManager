WinManager
==========

A classical windows type environment for vim6.0   

## Author
Name: 	Srinath Avadhanula 	  
Date:	2002-04-03  
Script Version: 2.3  

## Collector
Collecter: MwumLi
Update Date: 2015-11-27
Description: only to use conveniencely

## Twe Mode

1. `old mode` keep the same function as [winmanager](http://www.vim.org/scripts/script.php?script_id=95)  
2. `new mode` fix some bug and add some new functions :  
   1. avoid a blank window that appears when open nerdtree by winmanager 
   2. open winmanager automaticaly when vim start up by set `g:ifmicro_auto_open_winmanager`  


## Option

1. `g:ifmicro_auto_open_winmanager` : open WinManager automaticaly when vim start up  
   WinManager is closed by default  
   If you want it to automatically open :  

        let g:ifmicro_auto_open_winmanager=1
   
2. `g:ifmicro_use_origin_toggle` :open WinManager by new mode or old mode  
       WinManager is new mode by default  
    If you want to restore it to its original state :  

        let g:ifmicro_use_origin_toggle=1

