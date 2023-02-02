To reproduce:

* open src/main/kotlin/com/example/MyImplementation in IntelliJ
* Highlight `deprecatedFun` and press Option + Enter
* Select `Copy @Deprecated annotation from 'MyInterface.deprecatedFun' to 'MyImplementation.deprecatedFun'`
* The copied message doesn't escape quotes and the resulting code does not compile