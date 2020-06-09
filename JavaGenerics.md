# Generics:

    Genercics provides Type safety 
    Type Parameters
 #### Bounded Type parameters like Any class extends

     Class Test<T>{}
     Class Test<T extends Number>{}
     Class Test<T extends X>{} X can be either class or extends interface, if X is a class as a type perameter 
     we an pass either X type or it's child classes.
     if X is an interface as a Type parameter we can pass. either X type of its implementation classes.


    Class<T extends X>
    
####    Another Bounded type
        Class< A extends B & Runnable> 
        If we need to work with 2 classes or interfaces they ahv eto come up in order. with &.
        and we can extend only one class as a bounded type

    We can take any type of parameters based on our requirement.
    
###  Generics wildcard characters(?) 
