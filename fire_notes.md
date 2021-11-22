% Fire

Components
----------

The fire triangle shows three required components:

Fuel

:   to burn.

Heat

:   to start the fire.

Oxygen

:   to sustain the fire.

Consequences of fire
--------------------

-   Destruction of the data centre / server room itself.

-   Destruction of the harware inside the data centre / server room.

-   Loss of data caused by the destruction of data centre equipment.

-   Interruption to business continuity due to unavailablility of the
    data centre during or after a fire event.

Data centre-specific factors
----------------------------

1.  Data centres are not normally occupied in the normal course of work.
    In fact, a properly run data centre should rarely need humans inside
    it for extended periods. However, this means that fires are less
    likely to be noticed.

2.  Smaller server closets are particularly at risk of being used as
    unofficial storage areas for equipment, paperwork and
    indeed rubbish. Any solid object is potential fuel for a fire and
    shouldn’t be there.

3.  Data centres run at elevated temperatures to conserve
    electrical power. While an office might be at 21C, a server room may
    be at 25C.

4.  Elevated temperatures lead to lower relative humidity. Less dampness
    makes it easier for a fire to progress, and can worsen the effects
    of electrical sparks.

5.  A large amount of electrical equipment is present in a relatively
    small area.

6.  UPS systems include batteries. Lead-acid cells can vent hydrogen if
    overcharged, and lithium-ion batteries can easily catch fire.

Actions required
----------------

Prevention

:   of fire outbreak.

Mitigation

:   of effects a potential fire can have.

Detection

:   of a fire at the earliest possible stage.

Alerting

:   persons inside and responsible persons outside the data center
    environment that a fire has started.

Suppression

:   of the fire.

Fire classes
------------

Fires can be categorised into a number of classes depending on the type
of fire, . Knowing the class of a fire helps when choosing how to fight
it.

Prevention strategies
---------------------

The easiest prevention strategies involve reducing the availability of
fuel, heat and oxygen.

### Fuel

The easiest way to reduce the risk of fire in a data centre is to reduce
the amount of fuel:

-   All equipment should be either racked or wall mounted if relevant.
    Nothing should be allowed on the floor.

-   Decomissioned or unused equipment should be removed.

-   Wiring that is obsolete and unlikely to ever be reused should be
    fully removed.

-   The data centre must not be used as a storage area, either for
    equipment nor paperwork.

-   If a small working desk is provided inside the data centre, it must
    be for occasional use while performing a task and a “clean desk”
    policy must be in place.

-   Rubbish (e.g. packing boxes) must be removed immediately from the
    data centre after any work is done. If packaging is not going to be
    immediately disposed of, it should be stored elsewhere outside the
    data centre.

-   The data centre must be kept clean and free of dust.

-   Manufacturer’s instructions regarding batteries in particular must
    be fully complied with.

### Heat

In a closed volume of air, raising the temperature (as would be the case
in a data centre) has two effects:

-   Fires are easier to sustain.

-   Reduced humidity, causing increased risk of sparks.

### Oxygen

Oxygen is present at approximately in the air under normal conditions:

-   Normally this is just a physical fact that has to be lived with!

-   A very small number of data centres worldwide are equipped with a
    hypoxic air supply system which reduces the oxygen concentration to
    approximately . Fires cannot start or be sustained under
    these conditions.

-   Although hypoxic air systems are not commonly deployed, reducing the
    oxygen content is a key part of gaseous fire suppression systems,
    which function differently.

Detection methods
-----------------

Fire is detected normally by its byproducts: smoke and heat.

Smoke detectors

:   signal an alarm when they detect smoke particles in the air. Two
    methods:

    Ionisation

    :   detectors use radio isotopes to ionise the air, allowing it to
        conduct electric current. When a change is detected due to the
        presence of smoke, an alarm is triggered.

    Photoelectric

    :   detectors use a light source passed through the air that is
        incident on a photoelectric cell. When the light becomes
        sufficiently obscured by smoke, an alarm is triggered.

Heat detectors

:   signal an alarm based on temperature:

    Fixed temperature

    :   detectors activate when the ambient temperature exceeds the
        threshold temperature.

    Rate-of-rise

    :   temperature detectors activate when a the rise in temperature in
        a fixed period of time exceeds the maximum allowed.

Detector types
--------------

Area

:   detectors are what we are familiar with from non-data
    centre environments. A detection head is placed in the overall area.

    -   Air conditioning system will dilute the air sufficiently that
        large quantities of smoke will be required before an alarm
        is raised.

Aspirating

:   smoke detectors (ASDs) uses a fan to suck air from a sampling pipe
    with one or more sampling heads into a detection chamber.

Fire panel
----------

A local fire panel is often provided in a data centre. Its main
functions are:

-   Receive inputs from detection devices.

-   Alerting the presence of fire inside and outside the data centre
    using: audible warning devices (bell, syren, klaxon), visual warning
    devices (strobe), signalling staff and BMS.

-   Activating fire suppression systems, HVAC shutdown, power shutdown.

-   If the data centre is part of a larger facility, the data centre’s
    fire alarm/alerting/suppression system will need to be interlocked
    correctly with the main system.

-   Allowing remote visibility through the use of a remote annunciator,
    repeater or slave panel (same meaning for all!).

Extinguishants
--------------

Extinguishants are broadly divided into gaseous, removing oxygen and
water, removing heat.

Mitigation strategies
---------------------

Sometimes, fire will damage or destroy the data centre, or the building
in which it is situated.

-   Just as we have redundancy levels in power and cooling, consider
    having a secondary data centre location. This will involve
    duplication of hardware, mirroring of data and configuration, and
    may involve complex network routing.

-   Virtualisation can make it easier to migrate many workloads from one
    location to another.
	
