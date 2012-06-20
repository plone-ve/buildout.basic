Introducción
============

Este es una configuración básica de buildout que explica como instalar la librería `zope.component`_ 
generando un interprete Python llamado ``python`` local a tu entorno de desarrollo que incluye esta 
librería en su ``PYTHONPATH``.

Instalación
-----------

La instalación la realiza con los siguientes comandos: ::

  $ sudo pip install zc.buildout
  $ git clone https://github.com/plone-ve/buildout.basic.git replicar-python
  $ cd replicar-python
  $ buildout init
  $ ./bin/buildout
  $ ./bin/python
  >>> import zope.component
  
.. _zope.component: http://pypi.python.org/pypi/zope.component
