```mermaid
gantt
    title 3D Music Internship
    dateFormat  YYYY-MM-DD
section 3D Printing
    Install Orca:done, Orca, 2026-05-12, 1d
    Develop QGIS DEM Procedure: qgis, 2026-05-12, 2d
    Get Mercury Working: HG, 2026-05-12, 7d
    Design Tonga DEM STL        :tongadesign, after qgis, 1d
    Print Tonga DEM: tongaprint, after tongadesign
section Sensors
    Order Parts :done, order, 2026-05-11, 1d
section Solenoids
    Receive parts :milestone, receive, 2026-05-15, 1d
    Test MOSFET driver: driver, 2026-05-18, 2d
    Spec solenoids :spec, after driver, 1d
    Design fixture for ash dispersal: fixture, after solenoids, 3d
    Print fixture: fixtureprint, after fixture, 3d
    Test and iterate fixture: fixtureiterate, after fixtureprint, 8d
section Logistics and Milestones
    KC OOF: kcoof, 2026-05-13, 5d
    End of internship:milestone, 2026-05-22
