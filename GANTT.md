```mermaid
gantt
    title 3D Music Internship
    dateFormat  YYYY-MM-DD
section 3D Printing
    Install Orca:done, Orca, 2026-05-12, 1d
    Develop QGIS DEM Procedure: qgis, 2026-05-12, 2d
    Get Mercury Working: HG, 2026-05-12, 7d
   Tonga DEM        :a1, after qgis, 2d
section Sensors
    Order Parts :done, order, 2026-05-11, 1d
section Solenoids
    Receive parts :milestone, receive, 2026-05-15, 1d
    Test MOSFET driver: driver, 2026-05-18, 2d
    Spec solenoids :spec, after driver, 1d
    Design fixture for Glitter Machine: fixture, after solenoids, 3d
    Print fixture for Glitter Machine: fixtureprint, after fixture, 3d
section Logistics
    KC OOF: kcoof, 2026-05-13, 5d
