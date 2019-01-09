# Starship-Simulator

An alternative to the shitty ship forge ship building hoops that you have to go through in Starmourn.

Shorthand includes ss for superstructure, cap for capacitor, mod for module and plural forms for everything are accepted.

ss add (Component|Module) (Num): Adds a component, or a module to your simulation model.  
ss remove (Component): Removes a component. i.e. ss remove superstructure    
ss remove module (Num): Removes a module with an ID. i.e. ss remove module 4    
ss list (Component|Module): Displays a list of all components of that type, or of all modules. i.e. ss list engine name  
ss list (Component|Module) (Num): Shows the details of that particular component/module. i.e. ss list superstructure 2  
ss list (Component) (): Display a list of all components of that type, sorted by the paramter. i.e. ss list superstructure name  
ss clear (Module): Removes all modules from your current build. i.e. ss clear module    
ss clear (Components): Removes all components from your current build. i.e. ss clear component     
ss clear all: Removes all components and modules from your current build. i.e. ss clear all     
ss info: Shows all component information, as well as power usage, cycle usage, capacity and price. i.e. ss info  
ss info (Component|Module): Shows the details of the associated component/module that is attached to your current build. i.e. ss info component    
ss info (Modules) (f|full): Shows the full details of every module associated to your current build. i.e. ss info module f  
ss power (ID) (Num): For modules only. Turns 'on' however many modules of that particular ID you've specified. All modules left over will be turned off if they were previously turned on. i.e. ss power 4 2     
  
