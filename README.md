# ticonfig

A titanium cli plugin so that the build configuration can be read from the tiapp.xml file.

## Installation

~~~
$ [sudo] npm install -g ticonfig
~~~

## Usage

Add the following to your tiapp.xml:

~~~
  <plugins>
    <plugin version="1.0">yy.ticonfig</plugin>
  </plugins>
~~~

Then you can added the following, e.g. to your tiapp.xml file.

~~~
  <property name="cli.deployType">test</property>
  <property name="cli.includeAllTiModules" type="bool">true</property>
~~~

## Licence MIT