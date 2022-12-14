# Graphics Application Programming Final
For my final, I chose to make an orbit simulator. It originally started as a solar system creation sandbox, but over time I added new customization features that turned it into a more general "particle orbiter" simulation.
The program allows the user to design a planet/particle in the control panel, then place that planet/particle anywhere on the screen by right-clicking or clicking the middle mouse button.

## Planet Dimensions
Radius: The size of the planet/particle.

WidthSegments: The number of segments to use for width. Lower = more angular, higher = rounder.

HeightSegments: The same as WidthSegments, but for height.

## Orbit Speeds
OrbitX: The speed at which the planet/particle orbits the sun/core particle on the X axis.

OrbitY: The speed at which the planet/particle orbits the sun/core particle on the Y axis.

OrbitZ: The speed at which the planet/particle orbits the sun/core particle on the Z axis.

AxisRotationX: The speed at which the planet/particle rotates on its own X axis.

AxisRotationY: The speed at which the planet/particle rotates on its own Y axis.

AxisRotationZ: The speed at which the planet/particle rotates on its own Z axis.

## Texture Properties
Metalness: How metallic is the planet/particle's texture? Higher = shinier, lower = duller.

Roughness: How rough is the planet/particle's texture? Higher = rougher, lower = smoother.

FullBright: If 1, the planet/particle is unaffected by light, and is displayed with 100% brightness regardless of distance from the sun/core particle.

TextureOverride: If 0, the planet/particle has no custom texture. 1 = Mercury, 2 = Venus, 3 = Earth, 4 = Mars, 5 = Jupiter, 6 = Saturn, 7 = Uranus, 8 = Neptune.

PlanetColor: The color of the planet/particle. Only used if TextureOverride is set to 0.

## Camera Controls

X: The camera's position on the X axis (always looks at the sun/core particle).

Y: The camera's position on the Y axis (always looks at the sun/core particle).

Z: The camera's position on the Z axis (always looks at the sun/core particle).

## General Controls
TimeScale: Controls the speed at which the simulation plays.

ClearAll: While set to 1, all planets/particles are removed, and more cannot be created.
