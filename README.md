# dependencias

* descargar Apache Portable Runtime de [aqui](https://apr.apache.org/download.cgi) y compilar siguiendo los pasos a continuacion:

```sh
> tar xvfz apr-1.5.2.tar.gz
> cd apr-1.5.2
> ./configure
> make
> make install
```

* instalar openssl

```sh
brew install openssl
```

* descargar el instalador de activemq-cpp-library de [aqui](http://activemq.apache.org/cms/activemq-cpp-393-release.html) y compilar siguiendo los pasos a continuacion:

```sh
> tar xvfz activemq-cpp-library-3.9.3-src.tar.gz
> cd activemq-cpp-library-3.9.3
> ./configure --with-openssl=/usr/local/opt/openssl/
> make
> make install
```
