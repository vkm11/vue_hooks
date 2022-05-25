# Component LifeCycle Hooks:
## a vue component can go throgh 4 phases
1) Creation
2) Mounting
3) Updating
4) Unmounting

    Lifecycle hooks are methods tha allow us to hook into or tap into these diffrent phases in the lifecycle of a component and execute some code.

### 1) CREATION:-
Called after the instance has finished processing all state-related options.

      beforeCreate(), created()
      
### 2) MOUNTING:-
Called after the component has been mounted.
 
      beforeMount(), counted()
      
### 3) UPDATING:-
Called after the component has updated its DOM tree due to a reactive state change.

      beforeUpdate(), updated()
      
### 4) UNMOUNTING:-
Called after the component has been unmounted.

      beforeUnmounting(), unmounted()
    
### 5) MISC:-

      activated(), deactivated(), errorCaptured(), renderTracked(), renderTriggered()
 
