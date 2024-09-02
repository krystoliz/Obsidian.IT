User mode : safe environment for running apps without affecting core system
Kernel Mode : core components, low level tasks - memory, process scheduling, hardware
----------------------------------------------------
+ + modularity, 
+ + scalability (add more servers, or upgrade existing ones), 
+ + flexibility (layers updated or replaced independently without affecting entire system)
+ + security : isolate functions into separate layers
+ + centralized control : easier to control
+ - performance overload : each layer adds new tier which data must pass
+ - comm overload : inter-layer comm which decrease efficiency
+ - complexity : manageable but complex to implement
+ --------------------------------------------------------------------------------
+Other types of [[Operation System]]
+ microkernel : most essential function run in kernel : low level - space and thread management, user mode run others, device drivers and file systems
+ hybrid : both monolithic and microkernel
- exokernel : minimal abstraction, allow apps to directly manage hardware resources
- extensible os  : allow users to add new functionalities or modify without affexting core system
