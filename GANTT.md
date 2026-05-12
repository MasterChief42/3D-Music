```mermaid
gantt
    title 3D Music Internship
    dateFormat  YYYY-MM-DD
section 3D Printing
    Install Orca:done, Orca, 2026-05-12, 1d
    Get Mercury Working: HG, 2026-05-12, 7d
    Print Tonga DEM: tongaprint, after tongadesign, 2d
    Print Gulf DEM: gulfprint, after tongaprint gulfdesign, 2d
    Print Gulf DEM with RAFOS floats: gulfprint2, after tongaprint gulfdesign2, 2d
section 3D Elevation Models
    Develop QGIS DEM Procedure: qgis, 2026-05-12, 2d
    Design Tonga DEM STL        :done, tongadesign, 2026-05-12, 1d
    Design Gulf DEM STL with isobaths        :gulfdesign, after qgis tongadesign, 1d
    Design Gulf DEM STL with isobaths, RAFOS floats        :gulfdesign2, after qgis tongadesign gulfdesign, 3d
section Sensors
    Order Parts :done, order, 2026-05-11, 1d
    Test OpenOBS board and VCNL4010:obstest, 2026-05-13, 1d
    Pot OBS Sensors in PETG: obspot, after printheads, 1d
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
