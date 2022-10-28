Install JBang

```
curl -Ls https://sh.jbang.dev | bash -s - app setup
```

Stat a new terminal window.

To run class `hellocli`:

```
jbang hellocli.java
```

Note: dependencies are installed by JBang, based on //DEPS comment

or event:

```
./hellocli.java
```

Thanks to // /usr/bin/env 

To run Java somewhere in a GitHub Repo:

```
jbang https://github.com/eugenp/tutorials/blob/master/jbang/jbangquarkus.java
```

Note how code is fetched from remote repository, Quarkus is installed - out of nowhere, based on the //DEPS comment - and the application is started.

In a separate termina window, call the endpoint exposed by the application:

```
curl localhost:8080/hello
```


