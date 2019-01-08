# Starship-Simulator

An alternative to the shitty ship forge ship building hoops that you have to go through in Starmourn.

Shorthand includes ss for superstructure, cap for capacitor, mod for module and plural forms for everything are accepted.

ss add <Component|Module> <Num>: Adds a component, or a module to your simulation model.
ss remove <Component>: Removes a component.
ss remove module <Num>: Removes a module with an ID.
ss list <Component|Module>: Displays a list of all components of that type, or of all modules.
ss list <Component|Module> <Num>: Shows the details of that particular component/module.
ss clear <Module>: Removes all modules from your current build.
ss clear <Components>: Removes all components from your current build.
ss clear all: Removes all components and modules from your current build.
ss info: Shows all component information, as well as power usage, cycle usage, capacity and price.
ss info <Component|Module>: Shows the details of the associated component/module that is attached to your current build.
ss info <Modules> <f|full>: Shows the full details of every module associated to your current build.
ss power <ID> <Num>: For modules only. Turns 'on' however many modules of that particular ID you've specified. All modules left over will be turned off if they were previously turned on.
  
