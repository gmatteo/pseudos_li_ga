## Lithium

Li-low:

    Only 2s treated as valence, very efficient with normal hint = 20 Ha.
    This is not the version I'd recommend for GS applications but lots of MD calculations
    in large systems are done with 1s frozen in order to have more iterations and better statistics.
    In the PseudoDojo, we don't provide Li-low as we didn't manage
    to get good agreement with AE GS results.

Li-s:

    1s-2s treated as valence. normal ecut hint = 37 Ha
    This is the version provided by the "standard" PD table.

## Gallium

Ga-low:

    4s and 4p treated as valence. normal ecut hint = 25 Ha.
    It might be used for MD runs but, similarly to Li-low,
    we didn't manage to get good agreement with AE GS results.

Ga-d:

    4s/4p plus 3d semicore. normal hint = 40 Ha
    This is the version provided by the "standard" PD table.
    Recommended for standard GS applications.

Ga-spd:

    4s/4p plus 3spd semicore states. normal ecut hint = 57 Ha
    This is the version provided by the "stringent" PD table.
    Highly recommeded for GW and/or high-pressure applications.
