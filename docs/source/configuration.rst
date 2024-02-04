Configuration
=============

When it comes to using a third-party framework, the first thing that comes to mind is the setup, usage, and complexity of the framework. Crystal Sharp is developed by taking all of these considerations into account. Crystal Sharp is easy to configure and use.

To configure Crystal Sharp, the main initialization is required, which is very simple.

.. code-block:: c#

  IResolver resolver = CrystalSharpAdapter.New(services).CreateResolver();

Above is the line of code that registers the default implementations. In the above code, ``services`` is the ``IServiceCollection`` interface.
