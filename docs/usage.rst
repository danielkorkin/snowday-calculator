Usage Examples
==============

Below are some examples on how to use the ``snowday_calculator`` package.

**Basic usage:**

.. code-block:: python

    from snowday_calculator import predict, SchoolType

    # Predict the chance for a given zipcode.
    result = predict("12345", snowdays=2, schooltype=SchoolType.PUBLIC)
    print("Chance today:", result.chance_today())
    print("Chance tomorrow:", result.chance_tmrw())

For more details, see the API reference.
