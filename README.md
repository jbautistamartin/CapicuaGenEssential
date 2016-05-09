# CapicuaGen

CapicuaGen es un software que ayuda a la creación automática de
sistemas empresariales a través de la definición y ensamblado de
diversos generadores de características.CapicuaGenEssential agrega referencia a los generadores de caracteristicas Melchior, Gaspar, Balthazar,
                                        con lo que es posible generar un ejemplo funcional completo.

El proyecto fue iniciado por José Luis Bautista Martin, el 6 de enero
del 2016.

Puede modificar y distribuir este software, según le plazca, y usarlo
para cualquier fin ya sea comercial, personal, educativo, o de cualquier
índole, siempre y cuando incluya este mensaje, y se permita acceso el
código fuente.

Este software es código libre, y se licencia bajo LGPL.

Para más información consultar http://www.gnu.org/licenses/lgpl.html


## Instalación

Agrege la siguiente linea al archuivo GemFile de tu aplicación

```ruby
gem 'CapicuaGenEssential'
```

y ejecute:

    $ bundle

O instalela manualmente con el siguiente comando

    $ gem install CapicuaGenEssential

## Uso

CapicuaGen  permite comenzar a trabajar con él desde el mismo momento en que es instalado. Para obtener un ejemplo funcional simplemente ejecutamos el comando CapicuaGen con el parámetro example:

    $ capicuagen example

Se crearan los siguientes archivos:

* generator.rb: Ejemplo de un generador de codigo
* GemFile: Archivo de configuración de depencias para bundler .
* instnwnd.sql: Ejemplo de base de datos NorthWind, para Microsoft SQL Server

Revise el archivo generator.rb para tener una introducción a CapicuaGen.

## Contribuir

Reporte de fallos y solicitudes de pull son bien recibidas en https://github.com/jbautistamartin/CapicuaGen

