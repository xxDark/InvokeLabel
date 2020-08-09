Note that this repo will probably remain empty until I make a fully working transformer for it.  
This class file was hand made for JVM 8. Will not work properly on any other VM versions. HotSpot.

# Info
Stack frames are not pushed. JVM thinks that main is still running, although other methods are being executed.   
Tools like JStack with -F option (JVMTI) will not work and crash at some point.   
Only methods in the same class can be executed.
