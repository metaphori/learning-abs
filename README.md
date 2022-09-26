# Learning ABS (Abstract Behavioural Specification)

```bash
### Compile ABS code to JAva
$ java -jar lib/absfrontend.jar -j src/hello-world/hello.abs # Output goes to gen/ directory

### Execute application
$ java -cp gen/:lib/absfrontend.jar Hello.Main 
# Hello world!

### Compile to Erlang
$ java -jar lib/absfrontend.jar -e src/hello-world/hello.abs # Output goes to gen/erl
./gen/erl/run
# Hello World!

./gen/erl/run -P 8080 # cf Model API
```