AgileCyL Pucela Testing Days: PHP Taller
=========================================================

Usos
=====

Solo test unitarios e integracion
---------------------------------

Los tests dentro de la carpeta "tests"
Las clases PHP dentro de la carpeta "src".
Create your test under "tests" directory.
Create your code under "src" directory.

Correr todos los tst

$ bin/phpunit -c tests

Si queries ver la cobertura de código (require XDebug)

$ bin/phpunit -c tests/phpunit-codecoverage.xml.dist


All test
--------

Pruebas unitarias, integración y funcionales

1) Lanzar Selenium RC Server 

$ bin/launch_selenium.sh (execution permission: chmod +x bin/launch_selenium.sh )

2) Lanzar los test 

$ bin/phpunit -c tests/phpunit-complete.xml.dist

Deberías cambiar el namespace Acme por el tuyo y borrarlo.