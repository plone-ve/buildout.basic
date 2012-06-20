.. -*- coding: utf-8 -*-

Introducción
============

Este es un ejemplo de la configuración básica de `buildout`_ usada en el articulo 
`Replicación de proyectos Python`_, el cual explica como instalar la librería `zope.component`_ 
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
.. _buildout: http://plone-spanish-docs.readthedocs.org/en/latest/buildout/replicacion_proyectos_python.html
.. _Replicación de proyectos Python: http://plone-spanish-docs.readthedocs.org/en/latest/buildout/replicacion_proyectos_python.html
